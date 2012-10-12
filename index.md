---
layout: page 
title: diumoo / App
subtitle: 特别的豆瓣电台给特别的你
tagline: diumoo douban fm 豆瓣电台 mac osx lion 
description: "diumoo 是一个专门为 OSX 开发的豆瓣电台客户端，除了提供完整的电台收听体验，提供了诸多增强功能。"
---

{% include JB/setup %}

<style type="text/css" media="screen">
    #left{
        float:left;
        width:35%;
    }
    #right{
        float:right;
        width:65%;
        text-align:justify;
    }
    #right ol{color:#666;font-size:0.9em;}
    #right a{color:#66aacc;}
</style>

**小惊喜，diumoo lite 现在发布~**

猛击 [这里](http://diumoo.xiuxiu.de/static/app/diumoo_lite.zip) 下载!

新版本的改善

1. 全新 UI
2. diumoo Share 更方便的分享
4. Sandbox 机制
5. 自定义快捷键
6. More Channels Support
7. Retina Display 支持
8. 歌曲缓冲

**Bug Shooting**

lite 版本发现一个小bug，更改过自定义快捷键之后，重启应用会失效。这个 bug 
可以通过在终端中执行 
`defaults write com.diumoo.diumoo-lite shortcutDidRegistered 1` 
命令解决。此 Bug 将不会出现在正式版中。

噗，还有一些新功能，不过悬念还是留给 Mac App Store 版本（仍在审核中 TAT ）比较好
