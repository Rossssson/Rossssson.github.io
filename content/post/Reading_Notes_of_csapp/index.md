---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Reading Notes of csapp(2)"
subtitle: "Representing and Manipulating Information"
summary: "reading notes of Computer Structure: a programmer's perspective "
authors: [admin]
tags: [Reading Notes]
categories: [CS:app]
date: 2022-01-06T18:32:06+08:00
lastmod: 2022-01-06T18:32:06+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Image credit: [**Unsplash**](Miku-1)"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

# 前言

*Computer Structure: a programmer's perspective* （中译：深入理解计算机系统）是一本将计算机软件和硬件理论结合讲述的经典教材，通过描述计算机系统的实现细节，描述程序是如何映射到计算机系统上以及执行过程来理解计算机的行为。用这本书的读书笔记作为👴的第一篇post，一方面是觉得这本书上的内容是进一步CS学习的根本，另一方面也算是给自己开个坑，督促自己加油努力。最后用三玖老婆镇楼。（三玖是天！！！🎉🎊✨）

由于本书的第一章_A Tour of Computer System_是以自顶向下的方式对计算机系统进综述，因此这篇读书笔记从第二章_Representing and Manipulating Information_，讲述计算机如何存储、表示信息的基础开始。~~其实是因为开这篇笔记的时候已经把第一章看完了~~

# 2.1 信息存储

