# LinuxKernelComplie

编译的环境：

开发环境：Ubuntu 24.04.1 LTS
linux源码版本：linux-6.7.12
busybox源码版本：busybox-1.37.0
qemu-system-x86_64版本：QEMU emulator version 8.2.2

本文完成下列过程：

1.下载linux并编译linux内核源码
2.编译busybox
3.制作一个最小的根文件系统
4.qemu启动你编译好的内核和根文件系统

一、下载相关源码
下载Linux Kernle
Kernel下载网址：https://mirrors.edge.kernel.org/pub/
busybox下载网址：https://busybox.net/downloads/
二、安装必需的软件包
#sudo apt install libncurses5-dev build-essential openssl flex bison libssl-dev libelf-dev
#sudo apt install dwarves
#sudo apt install zstd
三、编译Linux Kernel

