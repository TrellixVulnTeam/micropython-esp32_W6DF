# micropython 资料收集
micropython是基于c编译的更集成化的开发方式，目前已编译的固件可以支持大部分固件的正常开发，如果需要进一步增加功能，也可以自行编译固件并烧录。但是其对如I2S自链接DAC、音视频编解码等功能支持不足，但是未来可期(真)
> 固件对应芯片：esp32-wroom32
## 参考教程
* micropython官方文档
* 01studio、星瞳科技中文文档
## 调试工具
* 串口终端工具
* 可视化串口助手(纸飞机yyds，侵删)
* 网络调试助手(调试无线功能用)
* 串口驱动 (CH340、CP210驱动)
## 烧录工具
* 烧录程序 flash_download_tool (烧录地址选择见mpy固件官网)
* 官方固件+01studio固件(lcd/lvgl两种)
## 开发环境
* uPyCraft
* Thonny(推荐)
## 库函数记录
* 基本函数
* 外设使用+屏幕显示，其中lcd固件库为01studio固件专用
* 附带01studio的lvgl固件函数以及lvgl官方源码，以便直接使用和自定义功能