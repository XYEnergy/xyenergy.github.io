---
layout: post
title: 保障终端安全
date: 2019-03-02 01:00:00
image: /assets/img/trustzone_head.png
description: 
category: '嵌入式终端'
tags:
- 可信
- 终端
- 安全
twitter_text: 保障终端安全
introduction: 为确保终端的安全性，设计中采用了具备可信功能的嵌入式设备。安全性由硬件实现保证，使得上层软件无法对其进行修改或绕过执行，实现了相当强的安全性。
---

为确保终端的安全性，设计中采用了具备可信功能的嵌入式设备，使用了TrustZone技术，充分利用了ARM自身的硬件设计优势，对CPU以及片内、片外的存储空间和外设都进行了安全性扩展。将运行空间划分成为无安全要求的普通执行区域和可信的安全区域，实现了程序的隔离和安全数据的存储管理。而由于这种安全性由硬件实现保证，使得上层软件无法对其进行修改或绕过执行，实现了相当强的安全性。

<img src="/assets/img/trustzone.jpg" alt="drawing" width="800"/>
