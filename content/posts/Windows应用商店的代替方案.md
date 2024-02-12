---
title: "Windows应用商店的代替方案" #标题
date: 2021-09-03T10:35:25+08:00 #创建时间
lastmod: 2024-02-12T10:35:25+08:00 #更新时间
author: ["MaxLen"] #作者
tags: 
- 微软
description: "滚！Windows Store！" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: "windows-store-gp"
draft: false # 是否为草稿
comments: true #是否展示评论
showToc: true # 显示目录
TocOpen: true # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: false # 底部不显示分享栏
showbreadcrumbs: true #顶部显示当前路径
cover:
    image: "" #图片路径：posts/tech/文章1/picture.png
    caption: "" #图片底部描述
    alt: ""
    relative: false
---

## 📘引入

### 你用Windows应用商店干吗？

Linus说过：微软的东西不能碰。但是Windows自带的应用商店可以说是诚意满满（~~主要是因为里面有很多UWP啊~~）里面的UWP大多数轻量、纯净、好用。

### 那你为什么要抛弃它？

那当然是因为Windows的自动更新啊！自动更新关闭后，商店就废啦！

### 那该怎么办？

别急，当然有代替办法

---

## 👂Store RG，不错的镜像站

### 用法介绍

![https://i.bmp.ovh/imgs/2021/08/939e773ada348159.png](https://i.bmp.ovh/imgs/2021/08/939e773ada348159.png)

整个网页界面十分朴素~

是不是一目了然？这玩意小白一看都会用——输入链接即可

但是软件们还需要一些依赖库，下面我们慢慢讲~

### 实例

以这款HyPlayer为例

![https://i.bmp.ovh/imgs/2021/08/671fc59305fe2ab2.png](https://i.bmp.ovh/imgs/2021/08/671fc59305fe2ab2.png)

只需要复制它在Windows Store中的[链接](https://www.microsoft.com/zh-cn/p/hyplayer/9n5td916686k?activetab=pivot:overviewtab)

就可以抓取到安装包了

但是**还没完呢！**

这些UWP是有**各自的运行库**的，这个网站也一并会把他们所需的运行库抓取下来，需要对应自己的电脑版本下载（注意有些文件后缀是「.BlockMap」，这不是可安装文件，我们不需要它）

![https://i.bmp.ovh/imgs/2021/08/3fab10433786be2c.png](https://i.bmp.ovh/imgs/2021/08/3fab10433786be2c.png)

### 网址

[Store RG](https://store.rg-adguard.net/)

---

## 😎还有一个骚操作

虽然一些应用在Windows应用商店里下架了，但只要你知道它的网址，你就依然可以在这里下载！

同时付费应用也可以在这里抓取到（~~只不过仍然需要商店验证就是了~~