# Object detection with YOLOv2

* Assignment for Coursera's [**Convolutional Neural Networks**](https://www.coursera.org/learn/convolutional-neural-networks/)

* Imports pre-trained weights for YOLOv2, implements two filters (score threshold and non-max suppression) to remove erroneous bounding boxes, tests it out on some sample images

* Fixed a bug in [yolo_utils.py](./yolo_utils.py) so that bounding boxes are plotted correctly


The weights are not included in this repository (they're ~200 MB). They can be found either on the [official YOLO website](http://pjreddie.com/darknet/yolo/) or by following Allan Zelener's instructions [here](https://github.com/allanzelener/YAD2K/blob/master/README.md)



# Main contents

* [Notebook](./object%20detection%20with%20YOLOv2.ipynb) contains the model; note that the YOLOv2 model and pre-trained weights are downloaded separately
