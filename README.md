﻿# [RTX51](https://github.com/OS-Q/RTX51) 

[![sites](http://182.61.61.133/link/resources/OSQ.png)](http://www.OS-Q.com)

#### 归属实时系统：[RTQ](https://github.com/OS-Q/RTQ)

### [RTX51简介](https://github.com/OS-Q/RTX51/wiki)

[RTX51](https://github.com/OS-Q/RTX51)有两个版本TINY和FULL，后者可替换选择很多，在此不收录。

RTX51 Tiny是一种实时操作系统（RTOS），是运行在8051内核上的RTOS，可以用它来建立多个任务（函数）同时执行的应用。RTX51 Tiny运行于大多数8051兼容的器件及其变种上。

非占先或多优先级的实时操作系统,是一个平级的时间片轮询实时操作系统,所有的任务平等运行。

RTX51 Tiny的程序用标准的C语言构造，由Keil C51 C编译器编译。用户可以很容易的定义任务函数，而不需要进行复杂的栈和变量结构配置，只需包含一个指定的头文件。RTX51TNY.LIB和RTX51BT.LIB库文件必须保存于库路径下,通常,该路径是"KEIL"C51"LIB文件夹。RTX51TNY.H必须保存在包含路径下,通常是"KEIL"C51"INC文件夹。


#### 关键特性

* 最大任务数：16
* 最大活动任务：16
* 代码空间需求：900字节最大
* 数据空间需求：7字节
* 栈空间需求：3字节/任务
* 系统时钟因子：1000～65535
* 中断等待：20个周期或更少
* 上下文切换时间：100～700个周期

8051单片机资源：https://github.com/sochub/8051

### [收录资源](https://github.com/OS-Q) 

* [文档](docs/)
* [资源](src/)

### [OS-Q = Open Solutions | Open Source |  Operating System ](http://www.OS-Q.com)