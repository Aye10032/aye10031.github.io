---

layout: post

title: "Ubuntu16.04环境下的科学上网"

date: 2018-05-21

tag: 教程

---

# 前言
笔者目前在学习过程中在Linux环境下下载一些资源的时候,由于某些众所周知的原因，资源的下载速度很慢或者甚至是基本无法下载，而在网上搜到的很多文档，要不就是如何在Linux系统下搭建SS服务端，就算是客户端很多也是语焉不详。所以倒腾了一下之后将方法分享在这里

### 你需要准备的：
> 一个SS服务器，搭建不是本文讲述的要点，请查阅 [上一篇](https://aye10031.github.io/2018/05/none/) 

# 开始
首先还是下载SS，不过多阐述：
> 我的系统是Ubuntu的，因此使用一下指令：
> ```
> apt-get install python-pip
> pip install shadowsocks
> ```
> Debian内核的其他系统同理      
> 而对于红帽内核的(例如CentOS)，则使用如下指令：
>```
>yum install python-setuptools && easy_install pip
> pip install shadowsocks
>```