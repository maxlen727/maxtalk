---
title: "Hexo主题上手实操：从Fluid到Icarus再到Nexmoe" #标题
date: 2021-10-03T10:35:25+08:00 #创建时间
lastmod: 2024-02-12T10:35:25+08:00 #更新时间
author: ["MaxLen"] #作者
tags: 
- 博客
- 建站
- 美化
description: "闲来无聊，给Hexo博客换个主题" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: "hexo-theme-change"
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

### 🎨前言

今天无聊，看着这平淡无趣的博客主题，突然想换个主题

![https://i.bmp.ovh/imgs/2021/10/6ffbb519f78fa3d9.png](https://i.bmp.ovh/imgs/2021/10/6ffbb519f78fa3d9.png)

我突然想起了这个大佬

![https://i.bmp.ovh/imgs/2021/10/69a599902539974c.png](https://i.bmp.ovh/imgs/2021/10/69a599902539974c.png)

又想起了它的[博客网站](https://blog.whatk.me/)：

![https://i.bmp.ovh/imgs/2021/10/5bdcc365bb939377.png](https://i.bmp.ovh/imgs/2021/10/5bdcc365bb939377.png)

哎？好像还蛮不错的啊

所以我决定：换！

---

### 🚗从Fluid到Icarus

先安装它

| npm install -S hexo-theme-icarus |
| --- |

然后启用它！

OK，搞定了。

这么简单？配置文件呢？

不管了，先本地预览一下！结果…

![https://i.bmp.ovh/imgs/2021/10/d7df34135bd601cd.png](https://i.bmp.ovh/imgs/2021/10/d7df34135bd601cd.png)

哈哈，貌似缺了个依赖包，装！

![https://i.bmp.ovh/imgs/2021/10/f7ff401519010d07.png](https://i.bmp.ovh/imgs/2021/10/f7ff401519010d07.png)

？？？不对啊！怎么长这个样！

![https://i.bmp.ovh/imgs/2021/10/e23eefc7f5bdf226.png](https://i.bmp.ovh/imgs/2021/10/e23eefc7f5bdf226.png)

然后我又到[他们的Github](https://github.com/ppoffice/hexo-theme-icarus)上研究了一下，进入了[官方文档](https://github.com/ppoffice/hexo-theme-icarus)。~~所以我们要新建`_config.icarus.yml`文件~~，哈哈，原来已经有一个了

![https://i.bmp.ovh/imgs/2021/10/2a4ac1ff7849c675.png](https://i.bmp.ovh/imgs/2021/10/2a4ac1ff7849c675.png)

那我们就简单配置一下它，差不多了。

还是很简单的。

![https://i.bmp.ovh/imgs/2021/10/dcd38e66299a59bb.png](https://i.bmp.ovh/imgs/2021/10/dcd38e66299a59bb.png)

![https://i.bmp.ovh/imgs/2021/10/7ce5083827a853f4.png](https://i.bmp.ovh/imgs/2021/10/7ce5083827a853f4.png)

但是！你可以看见我们的评论插件可以自动适应深色模式和浅色模式（写文章时我的电脑处于深色模式），但博客站不行！并且这个主题里，我的头像显示也不正确！

再换！

---

### 🚍从Icarus再到Nexmoe

这个其实就很简单了，因为它是国人开发，配置文件是中文的，并且我之前已经安装过Nexmoe了。

![https://i.bmp.ovh/imgs/2021/10/d1ddce3e417422e4.png](https://i.bmp.ovh/imgs/2021/10/d1ddce3e417422e4.png)

来啊，我们先看一下@折影轻梦（Nexmoe主题制作者）的博客

![https://i.bmp.ovh/imgs/2021/10/05b99d010dea736c.png](https://i.bmp.ovh/imgs/2021/10/05b99d010dea736c.png)

很不辍啊。

但是它也没有完美的暗黑模式支持，写到这里，突然想放弃，要不回去养老？

不行！

理由很简单：那个主题我用腻了！不管它，我们继续整！

最后总算差不多弄好了。

但这个主题就挺邪门的。它的分类不是嵌套的，多个分类竟然会是自成一体，没有嵌套，这点很难受。