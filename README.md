# LanOS -- 梳理linux0.12知识点系列

	这个工程的目标是梳理《Linux源码剖析》的知识点并从0.12版本的源码中抠出部分代码构建一个
	能用现代linux发行版方便编译的迷你系统，从而验证各个知识点

## 引用资源

* [《Linux源码剖析》最新的电子版 ](http://www.oldlinux.org/download/CLK-5.0-WithCover.pdf)
* [ linux 0.1x源码 ](http://oldlinux.org/Linux.old/kernel/0.1x/)
* [ oldlinux官网 ](http://www.oldlinux.org/)
* 《ORANGE'S:一个操作系统的实现》

感谢赵炯博士，感谢于渊老师，并致以最高的敬意！

## 本教程的特点

* 大量参考linux0.12的设计思路建立demo，有助于之后阅读linux源码
* 将尽可能多的linux中汇编实现的代码用c重新实现，提高可读性，降低学习成本

## 知识点目录

* [如何编译和运行demo](https://github.com/freelw/LanOS/blob/master/doc/how_to_build.md)
* [梳理linux0.12知识点系列 之 让汇编到C不再遥远](https://github.com/freelw/LanOS/tree/master/demos/protect_mode_demo)
* [梳理linux0.12知识点系列 之 a20地址线](https://github.com/freelw/LanOS/tree/master/demos/a20_open)
* [梳理linux0.12知识点系列 之 8259A的初始化和时钟中断](https://github.com/freelw/LanOS/tree/master/demos/init_8259a)
* [网上相关资料整理](https://github.com/freelw/LanOS/blob/master/doc/questions.md)

## 血与泪
* [跳转到用户态](https://github.com/freelw/LanOS/blob/master/demos/user_mode_demo/readme.md)
* [初步调试fork](https://github.com/freelw/LanOS/blob/master/demos/fork_demo/readme.md)
* [fork+写时复制](https://github.com/freelw/LanOS/blob/master/demos/cp_on_write/readme.md)

