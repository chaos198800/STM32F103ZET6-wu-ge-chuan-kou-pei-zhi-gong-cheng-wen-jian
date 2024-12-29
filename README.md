# STM32F103ZET6 五个串口配置工程文件

## 资源描述

本仓库提供了一个基于STM32F103ZET6主控芯片的五个串口配置的工程文件。资源中包含了五个Keil工程文件，分别配置了五个串口：

- USART1：挂在APB2总线下
- USART2、USART3、USART4、USART5：挂在APB1总线下

## 功能说明

程序代码的主要功能如下：

1. **串口调试助手配置**：
   - 波特率：115200
   - 停止位：1
   - 数据位：8
   - 校验位：None
   - 显示和发送格式：十六进制
   - DTR和RTS：不勾选

2. **按键控制**：
   - 按下KEY0键后，串口调试助手将接收到十六进制下的41。
   - 随后，串口调试助手将以十六进制发送5a a5。
   - 开发板上的LED0和LED1将同时点亮。

## 使用说明

1. **下载资源**：
   - 下载本仓库中的五个Keil工程文件。

2. **导入工程**：
   - 将下载的工程文件导入到Keil开发环境中。

3. **编译与下载**：
   - 编译工程文件，并将生成的二进制文件下载到STM32F103ZET6开发板上。

4. **串口调试**：
   - 使用串口调试助手连接开发板的串口，并按照上述配置进行设置。
   - 按下开发板上的KEY0键，观察串口调试助手和LED灯的状态变化。

## 注意事项

- 请确保开发板的硬件连接正确，特别是串口和按键的连接。
- 在调试过程中，建议使用示波器或逻辑分析仪观察串口信号，以确保通信的正确性。

## 其他说明

- 本资源配合相关博客文章阅读效果更佳，博客文章详细介绍了该工程的实现原理和调试过程。

希望本资源能够帮助您更好地理解和使用STM32F103ZET6的串口配置功能。如有任何问题，欢迎在仓库中提出Issue。

## 下载链接

[STM32F103ZET6五个串口配置工程文件](https://pan.quark.cn/s/58d8785beee7)