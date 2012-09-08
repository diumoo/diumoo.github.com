---
layout: page
title: "diumoo / Usage"
subtitle: "I wish you can make full use of it!"
description: "diumoo 使用说明"
---
{% include JB/setup %}
<style type="text/css">
p{font-size:0.95em;color:#333;}
#main img{width:480px;height:auto;}
code{border:solid 1px #ccc;background:#eee;}
</style>

# diumoo 使用说明

## 探索特性

长话短说，我相信各位用户不会在使用 diumoo 的过程中遇到太多问题，在这里主要介绍一下 
diumoo 的一些需要额外说明的特性。

### 时间机器

时间机器这一功能用来记录您播放过的歌曲，并可以从历史记录中调出曾经播放过的歌曲播放。
为了使用时间机器，首先请点击主界面中的唱片集画面。此时将会弹出当前播放歌曲的详细信息
时间机器的启动按钮就在这里。顺便指出，您可以在这一画面中直接查看此专辑的详细信息，而
无需打开豆瓣网页。

![查看详细信息](/static/usage/showdetail.png)

点击“时间机器”即可浏览播放记录。如下图所示：

![时间机器](/static/usage/timemachine.png)

进入时间机器之后，您就可以自由查阅播放记录了，由于记录越多，时间机器开启的速度就越慢，
所以默认限制查阅刚刚播放过的 100 首歌曲。您可以在偏好设置中设置这一数值。

找到想要恢复的歌曲之后，点击 Restore 即可恢复播放，点击 Done 退出时间机器。

### diumoo Helper

diumoo Helper 是为方便您收听豆瓣音乐人和电影原声而设计的，我们提供了 Safari、Chrome、
和 Firefox 三种浏览器使用的插件。当您正确安装插件之后，就会在原来豆瓣页面播放音乐人
和电影原声的连接下方看到“在 diumoo 中播放”的字样。轻点连接就可以在 diumoo 中播放了。

![播放电影原声和艺术家](/static/usage/play_soundtrack_and_artist.png)

需要注意的是，在 Chrome 和 Firefox 会弹出对话框，为了方便起见，请选择“下次不再提示”，
当前保存下来的选项，可以采用以下方法重新设定。

Chrome 用户请清空
``Users/[您的用户名]/Library/ Application Support/Google/Chrome/Local State `` 文件

Firefox 用户请选择偏好设置，选择“应用程序”选项卡，在选项卡内找到 diumoo 对应的条目，将动作设置为
“使用 diumoo ”

### diumoo Share

在通常情况下，豆瓣分享连接将会导向官方豆瓣电台页面。为了使得 diumoo 用户的相互分享音乐
更为方便，diumoo 默认不分享到官方豆瓣电台，而使用 diumoo Share 。当您打开一个 带有 
\#diumoo 标签的音乐分享时，diumoo 将会自动播放这首歌曲。针对不使用 diumoo 的用户，也提供
指向豆瓣官方电台的连接。

![diumoo Share](/static/usage/diumoo_share.png)

要使用 diumoo share，在主页面右下点击蓝色的分享符号按钮，选择想要分享到的社交网络即可。


## 全局快捷键

由于在 Mac OS 的沙盒下实现多媒体键控制比较困难，故当前版本 diumoo 只支持全局快捷键，您
可以在偏好设置中设置这些快捷键，但是我们建议您保留我们默认的快捷键设置，如果这些设置并
不会与您其他应用程序的快捷键相冲突的话。

所有的默认快捷键都需要组合键 ``Command + Option`` ，即下图中蓝色区域所代表的区域。

![快捷键](/static/usage/shortcuts.png)

除此之外，绿色区域代表着播放控制键，具体设置如下：

+ _播放/暂停_：``;`` 
+ _切歌_：``'``
+ _红心_：``<`` 
+ _不再播放_：``>``

另外，橘红色的按键是一个特殊的组合键，用来直接显示 diumoo 的主界面，省去了移动鼠标的麻烦，
对应的按键为 ``/``。

