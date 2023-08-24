# USB_HUB_WCH
手上需要一个USB集线器，准备做一个。器件选型时找了找，什么Ti的TUSB系列啊，WCH的chxxx，芯动科技的C188（买不到，但它是国产的USB3.0欸！），不太想用国外的芯片（支持国产芯片！！！）最后敲定了沁恒的CH335F。

只做一个集线器太单调了就想能不能加些别的功能，比如：

* 多功能旋钮（先用旋钮编码，后边看看能不能换成FOC）
* USB读卡器
* USB声卡
* PC硬件资源监测，配合trafficmonitor插件
* 过流检测

#### 目录结构

* **0_Hardware**：PCB设计文件，立创eda或者ad
* **1_Firmware**：单片机固件
* **2_Docs**：存放芯片的datasheet等
* **3_Imgs**：存放图片

#### (Temp)芯片方案

USB-HUB芯片：CH334

多功能旋钮驱动芯片：stm32f030c6t6（忘了这个芯片带不带USB了。）

旋钮方案：数字电位器

OLED：0.91寸

#### 临时文字

![Snipaste_2023-07-06_23-28-31](.\3_Imgs\Snipaste_2023-07-06_23-28-31.png)

准备用到芯片的引脚图。封装是QSOP28。

qqqqqqqqqq!突然发现个台湾的芯片，VL822!!这个2.0的芯片方案做出来以后挑战一下画vl822高速板子

