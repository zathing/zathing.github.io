---
layout: post
title: "VMware 的那些坑"
date: 2019-10-17 13:51
comments: false
brief: “VMware 使用中的一些 Tips”
reward: true
tags:
	- 技术
---

VMware 是一款优秀的虚拟机软件，不过在使用过程中难免会遇到一些疑难杂症，这里统一记录下。

#### 0x00 物理机的各种功能键异常
这可能是 VMware 使用过程中最常遇到的问题，在开着 VMware 的时候，外面物理机的 Ctrl+C Ctrl+V 都可能失效。这种情况的解决办法也很简单粗暴：
> 在物理机的环境下多按几下 Alt 键

<!-- more -->

#### 0x01 VMware 里的 Chrome 浏览器有白色的页面
这个问题准备的说是 VMware 里的 Chrome 浏览器有无法渲染的页面，这是由于 VMware 里 GPU 未能正常工作导致的，解决办法如下：
> 关闭 设置 -> 高级 -> 系统 -> 使用硬件加速模式（如果可用）
