---
layout: post
title: "JAVA中的四种访问修饰符"
date: 2015-08-03 10:44:24 +0800
comments: true
categories: Android
---

| 作用域     | 当前类 | 同一package | 子孙类 | 其他package  |
| :-------: | :---: | :--------: | :---: | :---------: |
| public    |   √   |      √     |   √   |      √      |
| protected |   √   |      √     |   √   |      ×      |
| friendly  |   √   |      √     |   ×   |      ×      |
| private   |   √   |      ×     |   ×   |      ×      |

