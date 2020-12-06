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

**possible usage:**
对比两张图片的不同，或许可以解决修图阈值的问题

# The Story

* 注重隐私的照片管理软件。
* 当用户将本地照片上传网络平台时，对于风险进行提示。比如在微信朋友圈等相对私人的空间，风险较低，而在微博等相对开放的社区，风险较高。
* 当用户下载图片时，对于图片版权尽行提示。



## 隐私检测与提示

* 个人隐私

  * 面部信息
  * 指纹信息
  * 姓名、身份证号、学校等文字信息

* 他人隐私

* 敏感信息

  * 地理位置信息
  * 车牌信息

* 版权信息

  * 有版权信息的下载图片

    

## 照片处理

* 针对敏感信息一键打马赛克。
* 对于人脸等敏感信息，如果出现被ai技术认出的风险，可以进行自动美颜等处理，直到不被认出。



## 其他

既然是注重隐私的照片管理软件，**那么软件如何确保用户隐私数据的安全性，如何对数据加密，甚至不保留用户隐私数据**，是可以进一步考虑的。这也是用户信任软件的重要因素。
