---
title: 如何正确的下载EH上的种子
date: 2021-12-02 23:16:53
tags: 杂谈
---
众所周知，eh/ex上有许多图包，而在网页/各种app上观看不仅浪费配额，而且画质也不好，这时，我们可以选择下载种子

---
## 如何获取种子
（第三方app请自行查找）当我们打开eh网页版是，我们可以先确定其是否有种子提供：在评分的星星旁边有一个绿色的标志，如果是亮的，那就有种子。  
打开页面，我们可以看到在画廊概览页右边有torrent download（x），其中x代表现在有的种子数
> Tips
>有 多个种子时其上传时间和包含内容可能不同，所以请务必注意
>并非所有种子都是可用的，只有有information按钮的种子才能下载

---
## Personalized Torrent  ？Redistributable Torrent?
对于已经登录的你，种子有两种，Personalized Torrent和Redistributable Torrent。后面解释很详细，personalized，顾名思义，就是你自己专属的种子，会记录你的上传和下载，而redistributed不会做这些。如果你想分享种子，请务必分享redistributed的种子， ~~你也不知道对方是不是吸血鬼。~~

---
## Ehtracker
[在这里](https://e-hentai.org/home.php)，你可以看到你的personalized torrent的上传，下载，做种时常等信息。里面还有重置personalized torrent的按钮，以防你不小心分享了你的私人种子

---

## 怎么下载

首先，本人**绝对不推荐**使用百度网盘和迅雷下载种子（况且eh的压缩包是没有密码的）

> 网盘类：115离线（也得胆子大些，另外115使用transmission下载）
> 电脑：qbittorrent，aria2，transmission等
> Android：aria2，idm，adm等
> Android（爱折腾）：利用tome安装arch/Ubuntu的容器及桌面环境（推荐root使用），再安装qbittorrent（如果你不得不用手机下载还想大量上传的话这个也值得一试）
> 用硬盘大的VPS下载（aria2）

当然，下种子方法多的去了，你可以自行去Google上搜索

---
### others
#### 私人种子转换
在你的私人种子中，tracker是这样的：`http://ehtracker.org/画廊id/你的识别码/announce`
在一般种子中是这样的：`http://ehtracker.org/画廊id/announce`
很明显，你的识别码决定了这个种子是否是私人种子

---
官方wiki页面：[https://ehwiki.org/wiki/EHTracker](https://ehwiki.org/wiki/EHTracker)
