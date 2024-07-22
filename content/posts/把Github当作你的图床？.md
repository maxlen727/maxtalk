---
title: "把Github当作你的图床？" #标题
date: 2023-07-17T10:35:25+08:00 #创建时间
lastmod: 2024-02-12T10:35:25+08:00 #更新时间
author: ["MaxLen"] #作者
tags: 
- 私有化
- 网站
description: "早年间我写blog就是把照片都托管到公开图床上了，结果现在很多图片都丢了，很影响文章阅读和保存，放在Github上可能靠谱一些" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: "img-river"
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

# ☠为什么不推荐使用公开图床

早年间我写blog就是把照片都托管到公开图床上了，结果现在很多图片都丢了，其中不乏有珍贵的照片，现在这些都已遗失，想再追觅，又到何处寻呢？

总之就是，公开图床非常不靠谱！谁又知道那些公开图床什么时候会跑路呢？

---

# 🕶️其一：PicGo

这个应该算是个明星产品了，主要也是白嫖Github来的。网上的教程非常多，并且这玩意是用[**electron-vue**](https://github.com/SimulatedGREG/electron-vue)开发的，我对其非常厌烦，所以不多介绍，请诸位自行上网查询教程吧！

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.1v2y0p2qnchs.webp)

[如何利用 Github 搭建自己的免费图床？](https://zhuanlan.zhihu.com/p/353775844)

---

# 🌿其二：PicX

听名字感觉是PicGo的升级版，原理和PicGo相同，都是嫖的Github公开仓库。

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.5vcfftzj8100.webp)

其不同在于它没有客户端，只是一个简单的网页。

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.7gb8jd2p0000.png)

### 🍂PicX官方服务

项目地址在这里‣，下方给出了官方使用地址，可以直接用官方的网页进行托管。

**然而**，我想去看使用文档时这个官方文档入口竟然打不开了。再看这个开源项目的盈利方式：

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.5yc1suo30bo0.webp)

额，好吧，赞赏码。这个网站真是有摇摇欲坠之势。所以还是自己用vercel部署一遍吧。

### 🍃Vercel，启动！

二话不说先把这个项目fork了

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.2mr08viovyc0.webp)

**Vercel，启动！**

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.528h5iysfmg0.webp)

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.11ixy2e586gw.webp)

很快啊，啪的一下就好了！

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.4pqeb6uxob60.webp)

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.6bfhuf0i3300.webp)

### 😊使用

我们先创建一个[token](https://github.com/settings/tokens/new)

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.170npn1n1o3g.webp)

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.3148ksdgk960.webp)

复制一下，然后进入PicX网站里，直接自动配置就完事了

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.6b0tomgosu00.webp)

上传一个图片试试看

![image](https://github.com/maxlen727/picx-images-hosting/raw/master/image.6abtbuklo0c0.png)

![Atri](https://github.com/maxlen727/picx-images-hosting/raw/master/Atri.1y1aaka3jvk0.webp)

非常方便。并且还可以使用jsDelivr/Statically之类的CDN加速。


