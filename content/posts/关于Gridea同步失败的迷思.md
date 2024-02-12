---
title: "关于Gridea同步失败的迷思" #标题
date: 2022-08-03T10:35:25+08:00 #创建时间
lastmod: 2024-02-12T10:35:25+08:00 #更新时间
author: ["MaxLen"] #作者
tags: 
- Gridea
- 博客
- 小记
description: "Gridea同步又失败了？！" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: "gridea-push"
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

我是用Gridea写作、发布文章、同步博客的。这真的是一款比较人性化的工具（傻瓜式，正常人能用明白），至少比我之前用过的Hexo、WordPress、docsify好太多。

但是用过Gridea的同学可能就知道它同步经常失败，并且是谜之失败。官网也没说解决方法，就让你F12打开开发者工具自己看错误自己排查。

曾经我以为是网络问题，就使用了代理，结果还是失败，反倒是去掉代理后又成功了。（我的代理没有问题啊，可以流畅看Youtube直播）之后再用这个方法又不管用了。

> 2023年的我补：估计是Gridea自带的git不走代理，也许用TUN模式代理就可以了
> 

Gridea的同步是时好时坏的。

不过我最近一直在积极更新我host文件里的Github解析地址，现在用的话照样会失败，不过多试几次就成功了。

希望能给用Gridea的小伙伴提供一些帮助，哈哈。