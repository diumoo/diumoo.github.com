---
layout: page 
title: diumoo / App
subtitle: 关于 Mac App Store 版与直接下载版的说明
tagline: diumoo douban fm 豆瓣电台 mac osx lion 
description: "diumoo 是一个专门为 OSX 开发的豆瓣电台客户端，除了提供完整的电台收听体验，提供了诸多增强功能。"
---

{% include JB/setup %}

# 关于两个不同版本的说明

diumoo 的 Mac App Store 版与直接下载版在主要的音乐播放功能上基本相同，
但是受限于 Mac App Store 强制要求的沙箱限制，部分功能未能实现。

以下功能在直接下载版存在而 Mac App Store 版不能实现：

1. 多媒体键控制。（因为沙盒的控制，无法使用相关的 API ）
2. 更新 iChat/iMessager 状态为音乐信息。（因沙盒限制，无法传递信息给 iChat/iMessager)

反过来，Mac App Store 版由于沙盒的存在，具有更好的安全性，请根据您自己的需要选择
对应的版本。
