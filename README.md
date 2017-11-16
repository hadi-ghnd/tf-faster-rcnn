# Description
This fork is to use the original tf-faster-rcnn for a task of multi-class vehicle detection in aerial images. The original faster R-CNN is used for Pascal-VOC data, and this is a customization suited for [VEDAI data](https://downloads.greyc.fr/vedai/) and also tested on [NWPU data](http://www.escience.cn/people/JunweiHan/NWPUVHR10dataset.html). It also provides an option to display Precision-Recall curve, after the testing is done.

# tf-faster-rcnn
A Tensorflow implementation of faster RCNN detection framework by Xinlei Chen (xinleic@cs.cmu.edu). This repository is based on the python Caffe implementation of faster RCNN available [here](https://github.com/rbgirshick/py-faster-rcnn).

**Note**: Several minor modifications are made when reimplementing the framework, which give potential improvements. For details about the modifications and ablative analysis, please refer to the technical report [An Implementation of Faster RCNN with Study for Region Sampling](https://arxiv.org/pdf/1702.02138.pdf). If you are seeking to reproduce the results in the original paper, please use the [official code](https://github.com/ShaoqingRen/faster_rcnn) or maybe the [semi-official code](https://github.com/rbgirshick/py-faster-rcnn). For details about the faster RCNN architecture please refer to the paper [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](http://arxiv.org/pdf/1506.01497.pdf).


### Here are some sample results of performing this model on two datasets:

![](hadi-ghnd/tf-faster-rcnn/data/imgs/figure.png)      |  ![](https://github.com/hadi-ghnd/tf-faster-rcnn/blob/master/data/imgs/figure_2.png)
:-------------------------:|:-------------------------:
Detection results in VEDAI |  Precision-Recal curve of each class


![]( hadi-ghnd/tf-faster-rcnn/data/imgs/figure_21.png )      |  ![]( hadi-ghnd/tf-faster-rcnn/data/imgs/figure_34.png )
:--------------------------------------------------:
Detection results in NWPU
