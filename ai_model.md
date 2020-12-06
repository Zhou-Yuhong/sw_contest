# 可能有用的AI

## TensorFlow Object Detection API

https://github.com/tensorflow/models/tree/master/research/object_detection#tensorflow-object-detection-api

**CAN RUN ON MOBILE** 

[TensorFlow Lite](https://www.tensorflow.org/mobile/tflite/)(TFLite) is TensorFlow’s lightweight solution for mobile and embedded devices. It enables on-device machine learning inference with low latency and a small binary size. TensorFlow Lite uses many techniques for this such as quantized kernels that allow smaller and faster (fixed-point math) models.

https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android

This is a camera app that continuously detects the objects (bounding boxes and classes) in the frames seen by your device's back camera, using a quantized [MobileNet SSD](https://github.com/tensorflow/models/tree/master/research/object_detection) model trained on the [COCO dataset](http://cocodataset.org/). These instructions walk you through building and running the demo on an Android device.

**possible usage**:

探测照片里的敏感信息



## Face Recognition

https://github.com/ageitgey/face_recognition

* find face in picture
* find facial feature
* identity faces in pictures

**possible usage**:

探测照片里的脸，并且提示用户，用户可以根据需要一键打马赛克



## OpenFace

https://github.com/cmusatyalab/openface



## face-api.js

https://github.com/justadudewhohacks/face-api.js

JavaScript face recognition API for the browser and nodejs implemented on top of tensorflow.js core

**it has some cool stuff**

Age Estimation & Gender Recognition



## pixelmatch

https://github.com/mapbox/pixelmatch

The smallest, simplest and fastest JavaScript pixel-level image comparison library, originally created to compare screenshots in tests.

Features accurate **anti-aliased pixels detection** and **perceptual color difference metrics**.

Inspired by [Resemble.js](https://github.com/Huddle/Resemble.js) and [Blink-diff](https://github.com/yahoo/blink-diff). Unlike these libraries, pixelmatch is around **150 lines of code**, has **no dependencies**, and works on **raw typed arrays** of image data, so it's **blazing fast** and can be used in **any environment** (Node or browsers).