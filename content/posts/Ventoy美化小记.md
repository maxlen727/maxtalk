---
title: "Ventoy美化小记" #标题
date: 2021-09-17T10:35:25+08:00 #创建时间
lastmod: 2024-02-12T10:35:25+08:00 #更新时间
author: ["MaxLen"] #作者
tags: 
- ventoy
- 美化
description: "美化一下咱们的Ventoy" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: "ventoy-mei-hua"
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

### 📚前言

闲来无事，给Ventoy美化一下吧。

官方对于主题插件的文档中提到：

> 当你第一眼看到Ventoy的时候，你是什么感觉？不是很漂亮对吧？现在你可以定制你自己的主题了！
> 
> 
> Ventoy 的启动菜单是基于 grub2 的，所以所有 grub2 的主题都可以应用在 Ventoy上面。
> 

那咱么就给它换个主题。

---

### 😀开始

[GRUB Themes - Gnome-look.org](https://www.gnome-look.org/browse/cat/109/order/latest/)是个好网站，我们可以直接在里面找引导主题。

![https://i.bmp.ovh/imgs/2021/10/890ea40ab90c355a.png](https://i.bmp.ovh/imgs/2021/10/890ea40ab90c355a.png)

这个主题叫[Sleek GrubBootloader themes [That greets you with your name]](https://www.gnome-look.org/p/1414997)，很好看。我就决定用它。

参考一下现成的Ventoy主题。

![https://i.bmp.ovh/imgs/2021/10/4e25554312f6b346.png](https://i.bmp.ovh/imgs/2021/10/4e25554312f6b346.png)

`theme`是最主要的文件，我们把之前仿Big Sur的grub主题文件替换一下。

结束了。~~水了一篇。~~