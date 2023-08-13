# Unicorn 硬件简述

- 此开发板的任何问题都可以通过邮件与 [Theo]( mailto:sihao.tsang@gmail.com ) 联系



## 硬件简述

Unicorn 设计参考了 YuzuKi 大佬的柚木PI-蜥蜴的设计，基于全志 V851s 芯片。

- SOC：单核 ARM Cortex-A7@900Mhz 运行 linux 单核 RISC-V E907@600Mhz 运行 RTOS
- NPU: 最大算力0.5Tops支持 支持TensorFlow、Caffe、Tflite、和Onnx等多种深度学习框架
- DDR：内置 SIP 64 MB DDR2
- Flash: 128MB SPI NandFlash 
- Display:   支持 1*2-lane MIPI DSI 输出，最大支持 1280x720@60fps
- Camera:  支持2-lan MIPI CSI 接口摄像头，最高视频采集分辨率 4M@30fps
- Wireless: 支持 2.4GHz WIFI 无线网络协议，以及标准蓝牙及低功耗蓝牙协议。
- Audio: 支持外接功放模块 <font color="orange">(注：测试版核心板未引出音频接口)</font>

- other: 引出绝大部分 GPIO



<img src="https://shzeng.cn/Hardware-Documentation/image/unicorn/unicorn-core.png" alt="unicorn-core" style="zoom: 50%;" />



