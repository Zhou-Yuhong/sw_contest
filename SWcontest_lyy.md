# SWcontest

### 从KAGGLE比赛中获取灵感

## idea1

基于[Text Normalization](https://www.kaggle.com/c/text-normalization-challenge-english-language)的办公轻量化交流系统，主要实现的功能有：

- 发送消息前的语境修正。包括缩写扩充，拼写检查，口语向书面语转化，[性别代词识别与检查](https://www.kaggle.com/c/gendered-pronoun-resolution)；
- TODO LIST：private and public；
- 强大的分组功能和能与分组对应的用户公文片段（像VScode中的用户代码片段）；
- 自然的团队交流功能，公共文件分享；
- 团队公共日程安排；
- 电子邮件系统，同时为电子邮件提供语境修正。

主要思路：

- 移动端存储文件，私人日程与自定义公文模板；
- 编辑好文本（包括电子邮件与APP内消息）时上传云端并返回校正建议；
- 在云端储存公共文件与公共日程安排，公共TODO LIST。



## idea2

基于[Cornell Birdcall Identification](https://www.kaggle.com/c/birdsong-recognition)的住宅旁鸟类识别系统。主要实现的功能有：

- 根据鸟叫or鸟巢外形or鸟类外形识别住宅附近的鸟类；
- [Identify bird species from continuous audio recordings](https://www.kaggle.com/c/the-icml-2013-bird-challenge)
- 根据习性做出应对。
- 有些过于趋向于“运用一个ml模型"，而不是真正做好一个软件，需要更自然的功能挖掘。

## idea3

基于google landmark recognition的公共平台照片预检查系统，主要实现的功能有：

- 用户在公共社交平台上传照片、视频前先在移动端提取特征，上传到云端，跑一遍地标、车牌识别，同时还可以~~和素颜对比~~，如果检测到照片内含有车牌，重要地标等，可以做出提示。如果照片内的人脸和素颜相差程度超过阈值，可能会被认出时做出提示。

## 

