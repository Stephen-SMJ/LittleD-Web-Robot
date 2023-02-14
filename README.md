# LittleD Web Robot
## 小D是一个在低代码平台上的指引机器人，当用户进入平台时，可以通过小D快速创建应用和模板
它可以与用户进行特定的语音和文本交互。使用Websocket协议进行与客户端的实时通信，使用Flask框架搭建后端，使用PocketSphinx进行语音识别。使用PyHanlp进行文本分词，提取关键词用来语义理解。使目前主要功能:
（一）页面与功能跳转：语音或文字输入跳转到XXX页面/系统/ 我要设计一个XXX系统，即可跳转到对应页面或模板。
（二）发送邮件：使用ASRT进行语音转换。多段交互式，1.发送给XXX 2.输入邮件主题 3.输入邮件内容。
（三）智能手绘表单生成：开发人员可以在纸上手绘表单，上传至系统自动生成相同的表单样式。
收集公司人员手绘的200多张表单照片，经过数据增强后对表单中的所有input元素进行标注，使用YoloV3训练检测任务，检测出表单中的每个input的标签和位置并返回给前端，前端根据标签和位置生成相同样式的表单。使用flask编写接口并部署。
### 功能预览
![图片1](https://user-images.githubusercontent.com/67999981/218738664-fca5870f-e3a3-4802-b08c-d8e30b3c28c4.png)
![图片2](https://user-images.githubusercontent.com/67999981/218738675-16e396b7-1c32-451a-aab9-e6f6bee3bcf7.png)
### 优化方案
![图片3](https://user-images.githubusercontent.com/67999981/218738679-68fdb198-9354-4512-b66c-a34633baafe8.png)
### 优化效果
![test](https://user-images.githubusercontent.com/67999981/218738684-8788f744-9024-410f-88e5-d62f418e39f6.png)
