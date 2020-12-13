# Labview for PLC

#### 介绍
Labview for PLC
收集整理一些本人在Labview上位机项目中使用的PLC通讯协议。
主要针对西门子系列PLC。

#### 软件架构
01_LM_S7-1200_TCP：
该项目可通过TCP直接与S7-1200PLC通信。

02_LM_S7-1500_TCP：
该项目可通过TCP直接与S7-1500PLC通信。

03_LM_S7NetCom：
该项目为开源库S7NetCom的使用演示，
关于S7NetCom库的详细信息：https://dokuwiki.hampel-soft.com/code/open-source/s7netcom。

101_LM_Snap7：
该项目为Snap7库的使用演示，
关于Snap7库的详细信息：http://snap7.sourceforge.net。


102_LM_HslCommunication：
该项目为HslCommunication库的使用演示，
关于HslCommunication库的详细信息：http://www.hslcommunication.cn。

后续有待更新。

#### 安装教程
Labview安装：
Labview下载网址：http://download.ni.com/evaluation/labview/ekit/other/downloader。
选择
2018LV-WinChn.exe   （Labview2018中文版）
2018DSC.exe（Labview数据采集与记录模块，附带Kepware OPC Server 2016）


#### 使用说明
不含安装vip库的项目直接git clone即可。

03_LM_S7NetCom：
该项目需要点击项目Vip文件夹中的vip库，直接由VI Package Manager (VIPM)安装。

#### 参与贡献

