# 基于视觉语音的人机交互系统

![system picture](https://github.com/lilelife0/an-interactive-system-based-on-voice-and-vision/blob/master/图片1.png)<br><p align="center">
  系统框图
</p>

## 0.背景介绍
这是我在大一年级做的一项大创内容。我们的设计原型是一辆麦克纳姆轮小车。我们可以通过语音控制小车，同时小车也会通过摄像头获取环境信息，做出相应动作。


## 1.平台组成部分

* 主体&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;jetson nano<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;stm32

* 外设&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kinect v2<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;麦克风  音箱

* 算法&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;YOLO<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wukong-robot(语音)
 
## 2.调用到的库
我们使用了商汤开源的[pysot](https://github.com/STVIR/pysot)
## 3.具体算法
详见代码
## 4.可能的应用
* 自动跟随人的行李箱
* 家庭护理机器人
* 当家长不在，可以照看孩子的机器人（也就是家庭护理机器人）

