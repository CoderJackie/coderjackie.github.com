---
layout: post
title: "Xcode每次编译运行，都提示输入用户名和密码"
date: 2015-10-13 10:43:37 +0800
comments: true
categories: iOS
---
同事每次编译运行项目时，总是提示让输入用户名和密码，还要输入两次

{% img top /images/2015-10-13/image1@2x.png %}

解决方法如下：打开Launchpad -> 其他 -> 钥匙串访问

{% img top /images/2015-10-13/image2@2x.png %}

找到开发证书，打开，选择专用密钥，双击打开：

{% img top /images/2015-10-13/image3@2x.png %}

选择允许所有应用程序访问此项目，然后存储更改，输入密码，允许：

{% img top /images/2015-10-13/image4@2x.png %}

{% img top /images/2015-10-13/image5@2x.png %}

以后每次编译运行就不必多次输入用户名和密码了，妈妈再也不用担心我的学习~