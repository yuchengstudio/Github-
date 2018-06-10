* [1. 简介](#1-简介)
* [2. 使用Atmel Studio开发](#2-使用atmel-studio开发) 
   * [2.1 下载 IDE](#21-下载ide)
   * [2.2 安装 IDE](#22-安装ide)
   * [2.3 获取 SDK](#23-获取sdk)
   * [2.4 导入工程](#24-导入工程)
   * [2.5 编译工程](#25-编译工程)
   * [2.6 下载与调试](#26-下载与调试)
   
## 1. 简介
本 sdk 提供一个基于 Microchip 开发板，通过与 Wi-Fi 模块进行 AT 指令串口通信，实现与阿里云 SDS 直连的 IoT 物联网典型开发应用示例源代码。

下面分别讲解如何使用 Atmel Studio IDE 或者 AliOS Studio IDE，进行开发板相应的 SDK 编译与下载。 

# 2. 使用Atmel Studio开发

### 2.1 下载IDE
点击 [ Atmel Studio 下载](http://www.microchip.com/avr-support/atmel-studio-7)，进入开发工具下载列表页面。在列表中，选择适用于您 PC 系统类型的安装程序版本。

Tips:您也可以选择在线安装方式，但一定记得不要让电脑断网。


![下载 as](https://github.com/neooxu/MXkit-L21/blob/master/image/download_as.png)



### 2.2 安装IDE
下载完成后，解压缩，双击 “.exe” 安装文件，即可启动安装，一路默认，next到底即可。 

到安装目录中，双击 Atmel Studio.exe 文件，打开开发环境。 您还需更新 SAML21_DFP 组件至：“Atmel SAML21 Series Device Support (1.2.120) ” 版本，下载地址： 

[下载地址 1](http://packs.download.atmel.com/)   或  [下载地址 2](https://microchip.box.com/s/q9lbrcwdt7fhomqkzozjg1vry07xvdzg)，或 [下载地址3](http://developer.mxchip.com/fileDownload/583)

下载后，双击默认安装即可。
