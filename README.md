# MIPI CSI-2 to DVP Converter

This Project is **Work In Progress** by now.

If any questions, welcome for Issues & PRs   
如果有疑问，欢迎提交Issues或PR

**WARNING! This Project is not been fully productive tested, use at your own risk!**   
**警告！该项目未经充分的生产测试，使用需要你自己衡量**

### License

This project is licensed under the LGPL-2.1-or-later license. **DO NOT** download or clone this project until you have read and agree the LICENSE.     
该项目采用 `LGPL-2.1 以及之后版本` 授权。当你下载或克隆项目时，默认已经阅读并同意该协定。

### TODO

### Overview

This Project is used to convert MIPI CSI-2 signal to Parallel DVP based on TOSHIBA TC358748XBG bridge IC. The Interface is compatible with Raspberrypi Camera.   
该项目基于来自 TOSHIBA 的 TC358748XBG 桥接芯片，以实现 MIPI CSI-2 信号转接为并行 DVP。接口与树莓派摄像头兼容。

This Project include the GERBER and schematics of the hardware, which takes 4 layers JLC04161H-3313 Stacking.   
该项目附有硬件的 GERBER 和原理图与装配图纸，硬件采用四层 1.6mm JLC04161H-3313 叠层。

![PCB Preview Picture](https://github.com/AnterCreeper/csicam/blob/main/preview.jpg?raw=true)

Datasheet of TC358748XBG is included in the project, which requires external LICENSE.

### Pinout

<image src="https://github.com/AnterCreeper/csicam/blob/main/pinout.svg?raw=true" alt="Pinout" width="512">

generated using pinoutleaf at [https://splitbrain.github.io/pinoutleaf](https://splitbrain.github.io/pinoutleaf)
