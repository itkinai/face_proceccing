# Notes about face detection, recognition and e.t.c

## Table of Contents
- [Face processing](#face-processing)
  - [Detection](#detection)
  - [Recognition](#recognition)
  - [DataSets](#dataSets)
  - [Challenges](#challenges)
- [Other useful materials](#Other-useful-materials)
  - [Archetictures](#archetictures)
  - [Other](#other)

## Face processing

### Detection
* Constrained Local Neural Fields for robust facial landmark detection in the wild (https://www.cl.cam.ac.uk/~tb346/pub/papers/iccv2013.pdf)

* (1.09.16) Joint Face Detection and Alignment using Multi-task Cascaded Convolutional Networks - WIDER FACE 2016 second result

 - https://arxiv.org/pdf/1604.02878v1.pdf
 - https://deeplearningmania.quora.com/A-Fast-CNN-Face-Detection , http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Li_A_Convolutional_Neural_2015_CVPR_paper.pdf
 - github(Matlab): https://github.com/kpzhang93/MTCNN_face_detection_alignment
 - github(MXNet): https://github.com/pangyupo/mxnet_mtcnn_face_detection
 - github: https://github.com/DaFuCoding/MTCNN_Caffe

* (17.06.16) CMS-RCNN: Contextual Multi-Scale Region-based CNN for Unconstrained Face Detection (https://arxiv.org/pdf/1606.05413v1.pdf) - WIDER FACE 2016 first result

* (11.10.16) Dlib CNN detector (http://blog.dlib.net/2016/10/easily-create-high-quality-object.html)

* (11.06.16) Face Detection with the Faster R-CNN https://arxiv.org/pdf/1606.03473v1.pdf

* (9.11.15) Python OpenCV GPU Face Detection (https://github.com/alexanderkoumis/opencv-gpu-py)

* (2016) Compact Convolutional Neural Network Cascade for Face Detection
 - http://www.computeroptics.smr.ru/KO/PDF/KO40-1/400114.pdf
 - https://arxiv.org/pdf/1508.01292v3.pdf

* face-frontalization https://github.com/dougsouza/face-frontalization

### Recognition

new [1] SeetaFace Engine is an open source C++ face recognition engine, which can run on CPU with no third-party dependence (https://github.com/SCU-BRL/SeetaFaceEngine)

* FaceNet: A Unified Embedding for Face Recognition and Clustering (https://arxiv.org/pdf/1503.03832v3.pdf) (Triplets)

* Learning Descriptors for Object Recognition and 3D Pose Estimation (https://arxiv.org/pdf/1502.05908v2.pdf) (Triplets)


### DataSets
* Many datasets http://www.face-rec.org/databases/

* R CASIA ~10k ident, ~400k image 

* R Megaface #2 4.7 million faces, 672K identities, and their respective bounding boxes. Very dirty. (http://megaface.cs.washington.edu/dataset/download_training.html) 

* R Microsoft, Entities: 99k   Average Image#/Entity: 85
https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/

* R dlib face detection dataset http://dlib.net/files/data/dlib_face_detection_dataset-2016-09-30.tar.gz

* D WIDER FACE http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/

* D FDDB http://vis-www.cs.umass.edu/fddb/

### Challenges

* R Megaface #1 http://megaface.cs.washington.edu/results/facescrubresults.html 

* R Megaface #2 http://megaface.cs.washington.edu/results/facescrubresults_challenge2.html

* R Microsoft https://www.microsoft.com/en-us/research/project/ms-celeb-1m-challenge-recognizing-one-million-celebrities-real-world/

* R LFW http://vis-www.cs.umass.edu/lfw/results.html

* D WIDER FACE http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/

* D FDDB http://vis-www.cs.umass.edu/fddb/

---------------------------------------
## Other useful materials

### Archetictures
* Resnets
 - paper (https://arxiv.org/pdf/1512.03385v1.pdf)
 - Identity Mappings in Deep Residual Networks (https://arxiv.org/pdf/1603.05027v3.pdf)
 - Wide Residual Networks (https://arxiv.org/pdf/1605.07146v1.pdf) 
 - original models (https://github.com/KaimingHe/deep-residual-networks)
 - Training and investigating Residual Nets (http://torch.ch/blog/2016/02/04/resnets.html)

* Google Inseption
 - Pretrained models https://research.googleblog.com/2016/08/improving-inception-and-image.html
 - https://habrahabr.ru/post/301084/ , https://habrahabr.ru/post/302242/ , https://habrahabr.ru/post/303196/

* Batch Normalization 
 - https://arxiv.org/pdf/1502.03167v3.pdf
 - https://habrahabr.ru/post/309302/


### 2 Datasets
* Google Open Images	
 - http://academictorrents.com/details/9e9194e21ce045deee8d811481b4cd676b20b06b
 - https://github.com/openimages/dataset




### Other

* Object detection networks https://handong1587.github.io/deep_learning/2015/10/09/object-detection.html

* A curated list of deep learning resources for computer vision https://github.com/kjw0612/awesome-deep-vision#

* Deeplearning-papernotes https://github.com/dennybritz/deeplearning-papernotes

* Deep-Learning-Papers-Reading-Roadmap (https://github.com/songrotek/Deep-Learning-Papers-Reading-Roadmap)


* Systematic evaluation of CNN advances on the ImageNet https://arxiv.org/pdf/1606.02228v1.pdf

* Good ML blog (Paper Rewiew , literature sets, ... ) http://www.erogol.com/machine-learning/

* Neural-network-zoo http://www.asimovinstitute.org/neural-network-zoo/

* Deep-learning by Mail.ru 
	- https://habrahabr.ru/company/mailru/blog/306916/ 
	- https://habrahabr.ru/company/mailru/blog/311706/
	- https://habrahabr.ru/users/mephistopheies/topics/

* Acceleration package for neural networks on multi-core CPUs https://github.com/Maratyszcza/NNPACK

* This project is about explaining what machine learning classifiers (or models) are doing. https://github.com/marcotcr/lime

* ML books https://tproger.ru/books/9-free-books-about-machine-learning/

* PlaNet - Photo Geolocation with Convolutional Neural Networks 
	- https://github.com/dmakian/LittlePlaNet
	- https://arxiv.org/pdf/1602.05314v1.pdf