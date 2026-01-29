# build-your-own -x

## C++ : Write your own Operating System

### 教程

两个学习如何构建自己的操作系统的网址：
http://www.lowlevel.eu/wiki/Hauptseite 
https://wiki.osdev.org/Expanded_Main_Page

注意，通过上面两个网址，我们可以了解到，对于初学者，直接上手系统开发并不是很明智的选择。

在开始之前，先衡量一下自己是否有如下条件：
- 有多个项目的成功经验，是一名有经验的用户级应用开发者。通过构建操作系统的项目来丰富编程经验不是一个很好的选择。
- 有多年（若仅仅是学习，3~5年的编程经验即可）的多语言和多环境开发经验（如果是独立开发，要求会比较高，需要10年编程经验，其中包括几年的汇编或者C语言，并且将其用于系统编程的经验）。其中，关于UNIX的深度使用，是一个很好的系统设计开发参考经验。
- 有一定的项目管理能力，具有良好的设计能力。这是一个大项目，我们需要对你自己所进行的事有完整的目标估算和阶段性的检验复盘，良好的设计会让你的项目变得井井有条，并有效降低项目的代码复杂度。
- 有充足的时间和耐心（Linus在做自己的操作系统时，也花费了将近1年时间）。
- 有一定的英文阅读能力（基本上所有的参考资料，基础的如本教程中的wiki和视频，较难的如官方文档等，均为英文）。
- 不要抱有过高的预期。

视频教程：
https://www.youtube.com/playlist?list=PLHh55M_Kq4OApWScZyPl5HhgsTJS9MZ6M

### 环境

```
Intel Pentium Dual Core T4400
Linux Mint 17.1 (Rebecca)
Kernel 3.13.0-37-generic
KDE 4.14.2

sudo apt-get install
    g++
    binutils
    libc6-dev-i386
```