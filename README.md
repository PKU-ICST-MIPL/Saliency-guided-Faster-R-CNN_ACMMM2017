# Introduction
This is the source code of our ACM MM 2017 paper "Fine-grained Discriminative Localization via Saliency-guided Faster R-CNN", Please cite the following paper if you use our code.

Xiangteng He, Yuxin Peng and Junjie Zhao, "Fine-grained Discriminative Localization via Saliency-guided Faster R-CNN", 25th ACM Multimedia Conference (ACM MM), pp. 627-635, Mountain View, CA, USA, Oct. 23-27, 2017. [[PDF]](http://www.icst.pku.edu.cn/mipl/tiki-download_file.php?fileId=1007)

# Dependency
Our code is based on early version of [Faster R-CNN in MXNet](https://github.com/precedenceguo/mx-rcnn), all the dependencies are the same as it.

# Data Preparation
Here we use [CUB-200-2011] dataset for an example, we have organized the data as the form of [PASCAL VOC] dataset, which can be downloaded from [link](http://www.icst.pku.edu.cn/mipl/tiki-download_file.php?fileId=1006).

Download VGG16 pretrained model vgg16-0000.params from [MXNet model gallery](https://github.com/dmlc/mxnet-model-gallery/blob/master/imagenet-1k-vgg.md) to model folder.

# Usage

1. Start training by running ``python train_end2end.py --gpu GPUID``. This will train the network on CUB-200-2011 train.
2. Start testing by running ``python test.py --gpu GPUID``. This will test the VGG network on CUB-200-2011 test.

For more information, please refer to our [ACM MM paper](http://www.icst.pku.edu.cn/mipl/tiki-download_file.php?fileId=1007).

Welcome to our [Laboratory Homepage](http://www.icst.pku.edu.cn/mipl) for more information about our papers, source codes, and datasets.
