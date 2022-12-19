# Object detection With YoloV5 vs MobileNetSSDv2



<a href="https://object-detection.readthedocs.io/en/latest/?version=latest"><img src="https://readthedocs.org/projects/object-detection/badge/?version=latest"></a>


<a href="https://travis-ci.com/ehsan2754/object_detection"><img src="https://img.shields.io/travis/ehsan2754/object_detection.svg"></a>

<a href="https://pypi.python.org/pypi/object_detection"><img src="https://img.shields.io/pypi/v/object_detection.svg"></a>

* Free software: MIT license
* Documentation: https://object-detection.readthedocs.io.

## Project Details

In the past, the tasks of Computer Vision were to
classify MNIST numbers or to distinguish images of dogs from
images of cats. Now convolutional neural networks can perform
much more complex image processing tasks. One such task is
object recognition. In particular, YOLO and SSD neural net-
works can recognize instances of different objects and highlight
their bounding boxes in photos, even if there are several such
instances, they have different sizes and partially overlap.
Our purpose is to test these neural networks on our own
dataset with images of books. Our goal is to recognize books and
build bounding boxes for them using YOLO and SSD models.


## Dataset Host 
This is basically a set of pictures of my books in the dormitory! and Books are labeled by the author/publisher. We have 8 classes + background.
[roboflow books-umdmd dataset](https://universe.roboflow.com/cv-yovjv/books-umdmd/dataset/4/images/)


## Want to check how it works? 

our notebooks will help you out in [here](./notebooks). 

## Demo 

![](/docs/result-gif.gif)


## Credits

* [Aarohi](https://github.com/AarohiSingla) for her good video tutorials on Object Detection models.
* [ultralytics](https://github.com/ultralytics/yolov5) for his good of YOLOv5integration with roboflow.
* [roboflow-ai](https://github.com/roboflow-ai/tensorflow-object-detection-faster-rcnn) for the good dataset service and implementation of RCNN.
