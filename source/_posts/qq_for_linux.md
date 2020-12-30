---
title: 腾讯发布 Linux QQ 2.0.0 Beta2
date: 2020-04-01
tag: Linux
---

## 愚人节更新！
![QQ for Linux](https://s1.ax1x.com/2020/04/02/GGM7JU.png)

<!--more-->

## &emsp;四月一号，距上一次更新160天后qq for linux 迎来再一次更新，愚人节的玩笑？？？
  ![](https://s1.ax1x.com/2020/04/02/GGKfUK.png)
 #### 版本特性
  ![](https://s1.ax1x.com/2020/04/02/GGKj58.png)

---

## **概述**
#### QQ下载页面
![](https://static.oschina.net/uploads/space/2019/1024/220735_1SsJ_2720166.png)
#### 版本特性
  ![](https://s2.ax1x.com/2019/10/31/K5ddUS.png)

## **使用体验**
+ 深度应用商店已经上架了，这图标。。。两只企鹅。。。XD
 
  ![](https://s2.ax1x.com/2019/10/31/K50gtU.png)
+ 安装后启动器图标
  
  ![](https://s2.ax1x.com/2019/10/31/K504XR.png)
+ 登录界面。。。我看到了啥？？二维码！！！刚开始嘛，不能要求太多。。。
  
  ![](https://s2.ax1x.com/2019/10/31/K50HAK.png)
+ 主界面，这UI。。。仿佛回到了十年前～～～不对，我十年前还没有QQ号啊。。。
  
  ![](https://s2.ax1x.com/2019/10/31/K50jcd.png)
+ 简陋的设置界面
  
  ![](https://s2.ax1x.com/2019/10/31/K5c6Kg.png)
+ 版本号
  
  ![](https://s2.ax1x.com/2019/10/31/K5gKsg.png)

## **官方安装帮助**
### 一、如何选择安装包？
+ Linux QQ 目前支持x64（x86_64、amd64）、arm64（aarch64）、mips64（mips64el）三种架构，每种架构支持Debian系、红帽系、Arch Linux系、其它发行版中的一种或几种（未来可能继续扩充）。每一次发布均会提供架构和发行版的若干种组合支持的安装包，可按下面所述的规则进行选择。

    每一个安装包会按照形如如下的格式命名：
    ![](https://im.qq.com/linuxqq/images/setup_pic1.png)
+ 选择架构：
  
    根据你所使用的机器硬件架构选择相应的兼容架构类型（可通过uname -a查看）x64（x86_64、amd64）、arm64（aarch64）、mips64（mips64el）
+ 根据你所使用的linux发行版选择格式：
  ![](https://s2.ax1x.com/2019/10/31/K508mt.png)
### 二、如何安装？
+ 当前版本的Linux QQ依赖gtk2.0，安装Linux QQ前请确保你的系统已安装gtk2.0。以下是一些使用命令行安装gtk2.0的例子：
  
    ``` shell
    sudo apt install libgtk2.0-0 # Ubuntu
    sudo yum install gtk2.x86_64 # centos
    ```
+ 请参考你所使用的系统安装包管理器的使用说明来安装你所选择的Linux QQ安装程序，注意你需要root权限才能完成安装。在一些发行版中你可以通过双击文件管理器中的安装程序完成安装。以下是一些使用命令行来安装的例子：
 
    ``` shell
    sudo ./linuxqq_1.0.1-b1-100_x86_64.sh
    sudo rpm -ivh linuxqq_1.0.1-b1-100_mips64el.rpm
    sudo dpkg -i linuxqq_1.0.1-b1-100_armhf.deb
    sudo apt install -y /path/to/linuxqq_1.0.1-b1-100_amd64.deb
    sudo pacman -U linuxqq_1.0.1-ci-94_x86_64.pkg.tar.xz 
    ```
### 三、如何卸载？
+ 请尽量使用你安装时使用的对应方式来卸载Linux QQ（参考你所使用的系统安装包管理器说明）。同样需要root权限才能完成卸载。以下是一些例子：
  
    ```shell
    sudo rpm -e linuxqq
    sudo dpkg -r linuxqq 
    ```

---  
#### 文章结束，感谢阅读  ![](https://s2.ax1x.com/2019/09/27/uM30dH.gif)