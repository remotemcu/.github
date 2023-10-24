## About REMCU Project 

more info https://interrupt.memfault.com/blog/mcu-peripheral-forwarding

The **REMCU** project is a state of the art approach that will transform embedded development in the same way that microcontrollers have transformed the electronics industry. This solution combines the fun of embedded programming with the power of high level languages, as well as all of the PC effective tools like Jupyter Notebook, Matlab, etc.

![Standart interaction PC - MCU/SoC ](https://raw.githubusercontent.com/remculib/site/master/standart.png)

Usually, each change of firmware logic means uploading fresh C code onto a MCU device and resetting the device. With REMCU Project we’re able to send new instructions without further uploads and resetting. We can dynamically reprogram our devices in real-time!

![Chip Peripheral Forwarding](https://raw.githubusercontent.com/remculib/site/master/forwarding.png)

The **REMCU** Project is an Open-source cross-platform project designed for [***MCU Peripheral Forwarding***](https://interrupt.memfault.com/blog/mcu-peripheral-forwarding). This is an enabling technology that allows to map internal peripherals of various MCUs or SoCs to your personal or embedded computer as if these peripherals were a part of the computer. The tool can be thought of as a bridge that links your PC/embedded computer with low-level MCU/SoC’s peripherals such as *GPIO, analog input, CAN Bus, PWM, LCD controller, etc* without having to develop specific firmware, kernel drivers and other additional software. Your user space program gives access to all peripherals of a tethered chip using driver functions of SDK provided by MCU/SoC vendors or 3rd parties. You use the driver functions how you do it in firmware code. The REMCU Lib remotely executes them without the difficulties of writing a load of boilerplate code to serialize and transport your objects and invoke remote methods. You can get right down to business.

Let's have a look at the video below and see what opportunities and applications it provides:

[![REMCU DESCRIPTION](https://github.com/remotemcu/remcu_examples/raw/master/img/preview_description.png)](https://youtu.be/PJPl9Y96hA0)
