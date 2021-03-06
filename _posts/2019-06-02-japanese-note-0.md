---
title: "日语学习周记（至6月2日）"
tags: ["japanese"]
date: 2019-06-02 23:02:46
layout: post
excerpt: 记录一下日语学习进度。
categories: japanese
comments: true
---

5月24日我决心重新学日语之后，按计划到今天我应该已经背完五十音图了，但很不幸，因为我沉迷《明日方舟》<del>在线养驴</del>，所以进度拖延了。

为了解决背五十音图的问题，我写了一个 python 脚本，见[上一篇文章。](https://zhangyet.github.io/archivers/learning-japanese)。

5月31日，我拉了一个学日语的微信群，群里有日语专业的学生，也有日本从业人员。当然我并不认同社交化学习的理念，这个群主要的目的是社交。当然非常感谢该群的康老师，因为之前做这个五十音图工具的时候，我参考的是维基百科——但是没有仔细看，没有发现 ゑ ヱ 这个假名已经被去掉了——我还以为是前两年加了这个假名。

所以后来我重新用 go 写了这个工具 [gojuon](https://github.com/ZhangYet/gojuon)，把这个假名去掉了，之所以用 go 重构，是因为可以直接用二进制分发（发布 go module 比发布 python package 容易多了）。

另外我虽然不认同社交化学习，但我认为分享互助的社会还是很有用的，将新的知识纳入已有的知识体系也是——所以我才写这些没啥技术含量的代码。
