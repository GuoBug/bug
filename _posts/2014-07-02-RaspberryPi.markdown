---
layout: post
title:  " Pi 上的 Pidora 中文化"
date:   2014-07-02 22:51:27
description: "Raspberry Pi 上的 Pidora 中文化，如何使用 Raspberry Pi，如何使用 Pidora，将Pidora汉化的方法，在Pidora上安装中文，从Raspberry Pi 官方下载安装中文。"
keywords: "Raspberry Pi,Raspberry Pi 中文,Raspberry Pi 汉化,Pidora,Pidora汉化,Pidora中文,Pidora Pi"
categories:  bug
---

1. 安裝中文字形
# yum install cjkuni-ukai-fonts cjkuni-uming-fonts taipeifonts wqy-bitmap-fonts wqy-microhei-fonts

2. 安裝中文輸入法 gcin 或 scim
# yum install gcin
或
# yum install scim scim-tables scim-tables-chinese scim-tables-chinese-extra scim-array scim-chewing

3. 修改中文環境設定
# vi /etc/sysconfig/i18n
把
LANG="en_US.UTF-8"
改成
LANG="zh_TW.UTF-8"

4. 重新開機

功能表已改成中文
