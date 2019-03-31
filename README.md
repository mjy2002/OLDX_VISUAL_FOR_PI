
# 1 OLDX-Visual For PI图像导航项目  
<div align=center><img width="600" height="130" src="https://github.com/golaced/OLDX_DRONE_SIM/blob/rmd/support_file/img_file/logo.JPG"/></div>

  ____OLDX-Visual For PI图像导航项目囊括了OLDX机器人开发平台中所需的主要图像导航API，其采用通用接口的设计能适用于OLDX-FC和OLDX-QUADRUPED团队已经开发了一套完整的免费开源
  项目。项目主要包括了地标识别、地标跟踪、地标SLAM、人脸识别、巡线、避障等，项目所采用的硬件平台主要是OLDX通用机器人控制器，其STM32单片机+
  树莓派A3+的架构，因此该项目内所有软件程序主要适用于树莓派平台环境，在其他平台上应用请自行一致。该项目遵循GPL协议，能对DEMO内相关源码进行修改和二次开发。<br><br>

<br>

**-如果该项目对您有帮助请 Star 我们的项目-**<br>
**-如果您愿意分享对该项目的优化和改进请联系golaced@163.com或加入我们的QQ群567423074，加速开源项目的进度-**<br>

<br>

# 2 官方镜像介绍
____为方便开发者免去自行安装Linux系统软件的过程，我们提供了官方的SD卡镜像(下载地址为：)。请自行下载并使用项目内win32软件写入空白
SD卡中，该镜像采用Raspberry原生镜像和树莓派系统，预装了ROS Kinect、Opencv 2.4.9、QT和Kdevelop。集成了已经编译好的API软件并安装好了
CSI并口树莓派相机驱动能直接测试使用。另外树莓派默认使用IO口串口(ttyS0,最大波特率115200)与单片机进行通讯,镜像内所安装的机体软件如下：

软件|版本说明
-------------|-------------
ROS|Comm Kinect版本
Opencv|2.4.9
QT|QT5
Python|Python2 Python3
Kdevelop|1.3.1
aruco|3.0.3
serial|1.0.0
x11vnc|1.0.3

API软件|说明
-------------|-------------
Cube_Tracker|地标识别跟踪
Face_Tracker|人脸识别
Line_Tracker|巡线
Recorder|视频存储

**注：树莓派默认用户名为pi，密码为1**<br>
**上电后默认连接WIFI名LBm，密码为11111111(Win7用户可以使用猎豹Wifi，Win10可以自建)**

# 3 树莓派使用教程
## 3.1 使用VNC连接树莓派
___官方镜像中已经安装了VNC客户端但是其自启动较慢，因此我们使用x11vnc作为远程桌面连接树莓派，由于其目前没有加入自启动中所以需要人工
启动，方法如下：<br>
(1)打开WIFI等待树莓派连接上WIFI热点，查看树莓派连接的IP地址。<br>
(2)使用putty用SSH连接树莓派，输入账号pi,密码1，在控制台中输入x11vnc打开客服端服务。<br>
(3)使用项目内的VNC软件输入树莓派IP:5900(如192.168.191.2:5900)连接目标，账号同样是pi完成连接。

## 3.2 向树莓派中拷贝文件
___向树莓派中拷贝文件可直接使用U盘进行复制，另外可以使用项目内的WinSCP软件使用目标IP、账号和密码连接树莓派并直接进行拷贝。

# 4 API软件介绍
## 4.1 二维码(立方体)识别跟踪
<div align=center><img width="600" height="130" src="https://github.com/golaced/OLDX_VISUAL_FOR_PI/blob/master/support_file/img_file3/cube.gif"/></div>

___官方镜像中已经安装了VNC客户端但是

## 4.2 人脸识别跟踪
___官方镜像中已经安装了VNC客户端但是

## 4.3 巡线
___官方镜像中已经安装了VNC客户端但是

## 4.4 视频录制
___官方镜像中已经安装了VNC客户端但是

## 4.5 地标SLAM
___官方镜像中已经安装了VNC客户端但是

# 5 捐赠与项目后续开发计划
____如果您觉得该项目对您有帮助，也为了更好的项目推进和软硬件更新，如果愿意请通过微信捐赠该项目！
<div align=center><img width="240" height="300" src="https://github.com/golaced/OLDX_DRONE_SIM/blob/rmd/support_file/img_file/pay.png"/></div>





