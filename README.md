# YingQ · 嵌入式软件 / 机器人开发

我关注嵌入式 Linux 和移动机器人开发，做过从 ROS 2 导航、Qt 触控界面到 STM32 底盘控制的实车联调。

## 精选项目

### [2026 嵌入式竞赛 · 无人机移动起降基站](https://github.com/Mind2Real11/embedded-competition-2026)

我用 **ROS 2、Cartographer 2D 和 Nav2** 实现实车建图、目标点导航与绕障，并负责 Qt 上位机和 STM32 底盘运动。在 **RK3588 / ELF2** 上部署本地大模型，接入 **DeepSeek 和阿里云语音转文字**，用 **MQTT** 联通控制台、ROS 2 和底盘。

[看 ROS 2 实车成果](https://github.com/Mind2Real11/embedded-competition-2026#ros-2-实车成果) · [看 ELF2 端云 AI 与 MQTT](https://github.com/Mind2Real11/embedded-competition-2026#elf2-大模型语音识别与-mqtt) · [看比赛视频](https://github.com/Mind2Real11/embedded-competition-2026#比赛视频) · [看我的贡献](https://github.com/Mind2Real11/embedded-competition-2026#我的贡献) · [读技术摘要](https://github.com/Mind2Real11/embedded-competition-2026/blob/main/technical-overview.md)

<a href="https://github.com/Mind2Real11/embedded-competition-2026#ros-2-实车成果"><img src="https://raw.githubusercontent.com/Mind2Real11/embedded-competition-2026/main/demo-cover.jpg" alt="麦克纳姆轮底盘实车导航，点击查看 ROS 2 实车成果" width="640"></a>

### [第21届全国大学生智能汽车竞赛 · 蚂蚁搬家](https://github.com/Mind2Real11/smartcar-ant-moving-2026)

基于 **NXP RT1021 / MicroPython** 的双车协同搬运项目。主车按类别搜索目标，从车用红外视觉和 **LoRa** 指令配合，两辆三轮全向车共同完成对位、绕物和夹推。

[看双车实车成果](https://github.com/Mind2Real11/smartcar-ant-moving-2026#双车实车成果) · [看比赛视频](https://github.com/Mind2Real11/smartcar-ant-moving-2026#比赛视频) · [读主从车技术说明](https://github.com/Mind2Real11/smartcar-ant-moving-2026/blob/main/technical-overview.md)

<a href="https://github.com/Mind2Real11/smartcar-ant-moving-2026#比赛视频"><img src="https://raw.githubusercontent.com/Mind2Real11/smartcar-ant-moving-2026/main/dual-car-push.jpg" alt="两辆全向车协同推动玩偶越过黄线，点击进入比赛视频" width="640"></a>

<!-- 新项目使用同一结构：项目标题与仓库链接、一句话交付结果、个人负责范围、演示或技术链接。 -->

## 技术方向

- **机器人软件** · ROS 2、Cartographer 2D、Nav2、MQTT
- **嵌入式 Linux 与交互** · RK3588 / ELF2、C++、Qt 6、WebEngine、WebChannel
- **端云 AI** · 板端大模型部署、DeepSeek API、阿里云 DashScope ASR
- **底层运动控制** · STM32、FreeRTOS、RT1021、MicroPython、LoRa、全向轮运动控制
