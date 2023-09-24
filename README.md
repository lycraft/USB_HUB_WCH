# USB_HUB_WCH
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
