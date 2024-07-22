---
title: "来到Manjaro后叛逃Deepin" #标题
date: 2022-08-08T10:35:25+08:00 #创建时间
lastmod: 2024-02-12T10:35:25+08:00 #更新时间
author: ["MaxLen"] #作者
tags: 
- Linux
- 小记
description: "瞎搞使我快乐。最近我尝试安装Linux系统，没想到这一用就回不去了。" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: "manjaro-to-deepin"
draft: true # 是否为草稿
comments: true #是否展示评论
showToc: false # 显示目录
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

我想能装个Linux玩玩，因为我比较馋Linux的各大桌面环境~~（我这人特别喜欢看UI颜值哈哈）~~。

我第一个想到的Ubuntu。它毕竟是最广为人知的Linux发行版。所以我就下载了它的镜像，放到了我的U盘里。因为我的U盘是Ventoy，所以我就没有研究什么“ISO写入”“DD写入”。弄好之后我给分了40G空间准备开始安装Linux。

我在BIOS中设置首选启动项为USB设备，然后进入了Ventoy的grub界面，选Ubuntu，开始安装。我本以为它能识别到我的Windows，然后为我自动进行共存安装，但是事与愿违，它没识别到。无奈我只能手动安装。作为一个Linux小白，我茫然不知选啥分区格式，选啥挂载，以及下面的安装引导是个啥。

我在CSDN上查到一篇教程。分了`/` `/boot` `/swap` `/home`四个分区，安装引导选择的是安装到`/boot`。开始安装结果说什么“EFI XXXXXXXXXX”之类的，我就记住一个EFI，不过我以为问题不大，直接忽略。

接下来就是等待时间，我去饮了一杯茶~~（饮茶属于安装系统标准操作哈哈哈）~~。结果它竟然报错没法安装grub，并说这是个致命错误。我也不知道啥问题，就去网上搜了一些解决办法，并不能行。我断定是Ubuntu的问题，所以我又去下载了Mint的镜像，准备安装。

结果很不幸，Mint也没有识别到Windows系统，无奈我又只好手动安装。结果报错是一样的“EFI XXXXXXXXXXXX”。我直接崩溃，感到Linux与我八字不合。

我以为是Ventoy的问题，所以我当即格式化了U盘，使用正规写入工具以DD模式刷写了一遍，这次我选择的系统是Manjaro。信心满满重启安装！本以为能成功，结果还是失败。。。一样的错误。我准备手动修复grub，无奈ArchWiki的内容我看地迷迷糊糊，并没有看懂，试着执行了几句指令后并没有修复成功。

**Linux与我八字不合**

但是我不能放弃，因为这一次次地失败安装，让我反复原因，逐步接近正确答案。我决定再试一次。

之前我在BIOS设置的是USB设备为首选项。这次再试的安装途中我迷迷糊糊地摁下了`F9`（这个按键在我的BIOS中是选择引导盘的按键），结果竟出现了两个USB选项：`SanDisk` `SanDisk:UEFI`。我顿悟：肯定是BIOS默认引导位置错了，于是手动选择引导，重新安装。

这次非常顺利，安装成功！

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/20240212/image.37zof2zztxi0.webp)

后来使用Manjaro非常快乐，就是前期配置有点复杂。进入Arch神教前都听在吹AUR，进了神教才发现是真神。还是我大Arch用户神通广大、法力无边。

> 后来的我补：行行行，我当时写的时候把Manjaro和Arch一起概括了，真是极大的错误。Manjaro也不是很好的东西，慢于Arch的软件更新还可能出问题，得罪Archer们了

但是！最崩溃的来了！Windows已经被我打入冷宫了，所以我写博客要在Linux上写。但这个Gridea竟然在我的Manjaro上无法正常使用！自己编译的版本和别人编译的版本都试过了，就是白屏然后闪退！

> 后来我的我再补：现在回看感觉当时应该是缺了运行库吧

索性我一咬牙，来到了Deepin。

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/20240212/image.479rk2y0qcy0.png)

OK，那就写到这吧。估计马上开学了，我要快点写作业啦！
