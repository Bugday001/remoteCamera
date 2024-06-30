# remoteCamera
**待进一步开发**
调用其他设备的摄像头给电脑用。

## 涉及
- 视频流在网页和电脑端的传输
- 虚拟摄像头建立
- 视频流处理

## TODO
- [ ] 在局域网传输视频流，目前手机端要求https协议。只能在gitpod网站进行测试
- [ ] 创建虚拟摄像头，使用exhibition环境中的pyvirtualcam库可以调用obs创建虚拟摄像头，需要安装obs，不好。考虑DroidCam,他们似乎集成了obs相关插件到自己的app中。