# OBJECT
Object Detection using SSD in the simplest way possible. SSDs are very fast in Object Detection when compared to  like R-CNN or Fast R-CNN,
Therefore i have used SSD in this object detection 
we start by importing all important libraries like from i
mutils.video import FPS
import numpy as np
import imutils
import cv2
i use  Reading the network in a variable called net using cv2.dnn.readNetFromCaffe.
SSD is designed for object detection in real-time. Faster R-CNN uses a region proposal network to create boundary boxes and utilizes those boxes to classify objects. While it is considered the start-of-the-art in accuracy, the whole process runs at 7 frames per second.
How SSD is used in object detection?
Image result for object detection using ssd
SSD uses a matching phase while training, to match the appropriate anchor box with the bounding boxes of each ground truth object within an image. Essentially, the anchor box with the highest degree of overlap with an object is responsible for predicting that object's class and its location.
what is ssd?
Mobilenet SSD is an object detection model that computes the output bounding box and class of an object from an input image. This Single Shot Detector (SSD) object detection model uses Mobilenet as the backbone and can achieve fast object detection optimized for mobile devices
why ssd instead of R-CNN ?
SSD (Single Shot Multibox Detector), which is one of the deep learning techniques, provides object recognition at once with a different approach. While the region proposal and region classification are done in 2 stages in Faster R-CNN, in SSD technique, they do both in one convolutional neural network at once.also SSDs are very fast in Object Detection when compared to  like R-CNN or Fast R-CNN,
Therefore i have used SSD in this object detection 
