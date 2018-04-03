# 开箱教程
## 步骤1
- 请扫描包装盒上的二维码获取开箱教程及其它相关资源。
- 包装盒了有备用的插针，需要使用插针的小伙伴可自行焊接

## 步骤2
- 请使用USB转TTL连接电脑与ShareBoard，仅需连接GND, TXD, RXD即可，如图所示：
- 打开终端软件（如SecureCRT）连接对应的串口，参数为115200,8,N,1

## 步骤3
- 连接上MicroUSB供电，此时电源指示**红色LED亮**。
- **请注意！因为A0芯片的bug，断电后再上电的时间间隔需大于5秒，否则无法正常启动（电源指示LED不亮）**

## 步骤4
- 如果一切正常，上电后终端软件将显示RTT的启动界面，当见到```“I am ShareBoard!”```之后，既可以操作**按键K2**





## DEMO
![iMXRT1050_Chip](../Pic/ShareBoard_rtt_mpy_demo.gif)    


![Logo](../Pic/QRcode.jpg)
