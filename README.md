# USB_HUB_WCH
手上需要一个USB集线器，准备做一个。器件选型时找了找，什么Ti的TUSB系列啊，WCH的chxxx，芯动科技的C188（买不到，但它是国产的USB3.0欸！），不太想用国外的芯片（支持国产芯片！！！）最后敲定了沁恒的CH335F。

只做一个集线器太单调了就想能不能加些别的功能，比如：

* USB转TTL串口
* USB读卡器
* USB声卡
* PC硬件资源监测，配合trafficmonitor插件
* 过流检测

#### 目录结构

* **0_Hardware**：PCB设计文件，立创eda或者ad
* **1_Firmware**：单片机固件
* **2_Docs**：存放芯片的datasheet等
* **3_Imgs**：存放图片

#### 功能





qqqqqqqqqq!突然发现个台湾的芯片，VL822!!这个2.0的芯片方案做出来以后挑战一下画vl822高速板子