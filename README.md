﻿# VFD-Clock Designed By drinow
- 用IV-11制作的荧光数码管时钟

## 预计支持的功能
	1.USB连接
	2.温湿度显示
	3.RGB色彩变换
	4.静态驱动
	5.WiFi/蓝牙、红外控制
	6.uCOS-ii
	7.可以断电
	8.环境光感应

## 更新日志
- 2020.02.25更新
  - ESP8266基本功能已完成
  - 需要重新设计电源电路
  - 需要将USB更换为TYPEC，并重新调整外壳尺寸
  - 需要删除TM1812，因为无法达到100%占空比，无法实现动态驱动
- 2019.04.26更新
	+ 删除CH340晶振，并改为CH340C芯片
	+ 修改温湿度传感器位置到USB口下方
	+ 删去复位按键
	+ 其他细节调整
- 2018.03.12更新
	- 添加MCU最小系统
	- 添加了2个按键、2粒单色LED
	- 添加了串口电路、USB电路
	- 添加了部分电源电路
	- 添加了光敏电阻
	- 添加了温湿度传感器
	- 添加了6粒全彩LED
	- 添加了红外接收器


