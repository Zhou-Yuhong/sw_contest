# The Story

**注重隐私的图片分享管理软件：**

当用户使用该软件，将照片分享至各个平台时（比如微信私聊，朋友圈，微博等），在微信朋友圈等相对私人的空间，风险较低，而在微博等相对开放的社区，风险较高。软件对于照片进行隐私检测。

用户可以设置隐私检测的选项，软件也会根据分享平台的不同，提供隐私检测的建议。

照片会根据用户的选项进行自动修正（比如打码），用户也可以选择手动修改。



* 不同于图库等照片管理软件，该软件是用户分享生活的隐私检测的助手。界面类似于作业帮、小猿搜题等软件。





## 隐私检测与提示

* 照片自带的信息

  * 拍摄时间、地点等

* 个人隐私

  * 面部信息
  * 指纹信息
  * 姓名、身份证号、学校等文字信息
  * 聊天记录的头像、昵称

* 他人隐私

* 敏感信息

  * 地理位置信息
  * 车牌信息

  

## 照片处理

* 针对敏感信息一键打马赛克。
* 背景虚化等功能
* 图片判断主人公、陌生人：主人公不打马赛克，其他人打马赛克。
* 对于人脸等敏感信息，如果出现被ai技术认出的风险，可以进行自动美颜等处理，直到不被认出。







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













