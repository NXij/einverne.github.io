---
layout: post
title: "知乎上被删除的良心回答之油猴脚本"
tagline: ""
description: ""
category: 整理合集
tags: [Chrome, userscript, tampermonkey, ]
last_updated: 
---

今天偶然间看到一个知乎[问题](https://www.zhihu.com/question/52157612/answer/180534098)：“最良心的软件可以良心到什么程度？”，当时在 Google+ 上点进去粗略看了一样，看到油猴脚本也就坦然了，而添加到稍后阅读，在晚上回来之后准备细看时却惊讶于知乎屏蔽的速度，在尝试使用 Google，bing 和 web archive ，baidu 的历史记录之后终于找回了一些渣滓。

我在很早就已经推荐过 [Tampermonkey](http://einverne.github.io/post/2016/12/tampermonkey.html)， 也借此推荐过 [我用过的 Userscript](http://einverne.github.io/post/2015/08/userscripts.html) 。 而 Tampermonkey 我也用了很多年也曾总结过 Tampermonkey [同步](http://einverne.github.io/post/2016/12/tampermonkey.html)的功能。不过多少年过去了，很多脚本失效的失效，我自己之前写得找电影脚本也因为跨域问题，一直懒没有修复。

幸好看到这样一篇总结帖，看看这两年又更新出来多少新玩法。以下为从历史记录中搜出：

直接来看 油猴脚本能干啥：

- 直接观看各大视频网站的VIP 视频
- 去除各大视频广告，百度搜索广告
- 免费收听网易云320k 高音质音乐
- 高速下载百度云
- 去除各种验证码

在国内互联网广告满天飞的现在，这些功能无疑会吸引很多的用户。

下面列举一些非常好用的脚本，我在 <http://einverne.github.io/post/2015/08/userscripts.html> 中列出的脚本不在更新。

### 网易云高音质下载

在网页上听网易高品质音乐，在网页歌曲页面播放按钮上面也能看到下载歌曲按钮，或者下载歌词，封面，MV 等等。

地址：<https://greasyfork.org/zh-CN/scripts/23222>


###  百度网盘直接下载助手
这个插件，你可以使用它可以直接获取文件原始链接，这样你就可以使用第三方（IDM，Folx）下载了，再也不用使用百度云客户端的龟速了。
还可以多个文件选择，批量下载。


地址：<https://greasyfork.org/zh-CN/scripts/23635>

解决百度云大文件下载限制  <https://greasyfork.org/zh-CN/scripts/17800>

百度网盘的下载助手，一直在有效，失效，修复，有效，再失效的过程中，因为在 Linux 下很久不用百度云的客户端，而百度最近频频限制下载速度，并且在分享页面增加很多限制，只能使用客户端下载，这么多动作的背后，一方面是因为带宽和存储费用逐渐增高，却无奈找不到任何赢利点，另一方面也因为监管力度的加强。在网盘大战落下帷幕的时候市场上还能够坚持到最后的也就剩下百度，金山，乐视云，360，大大小小的众网盘纷纷宣布停止运营。百度在一家独大之后也是频频限制免费用户的行为，所以用这么多的脚本来提高百度的体验，还不如彻底的原理百度云盘。用自己的一点钱买一个 [Dropbox](https://db.tt/B0sJSIVy) 或者 Google Drive 反而要轻松很多呢。


### 一键离线下载
将网页上的磁力链接离线到网盘,在寻找电影的时候，这也是经常的动作，这个脚本将找电影，然后到离线的过程自动化了。

<https://greasyfork.org/zh-CN/scripts/22590>

### 免费看VIP 视频

直接在 greasyfork.org 搜索 VIP 即可。


