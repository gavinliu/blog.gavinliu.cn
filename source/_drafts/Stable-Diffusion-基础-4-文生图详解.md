---
title: Stable Diffusion 基础 4 | 文生图详解
date: 2023-09-03 15:21:54
tags:
  - Stable Diffusion
  - Stable Diffusion 基础
categories:
  - AIGC
---

## 前言

在前面三篇快速上手中，其实已经使用过文生图功能了，但只用到了提示词+生成功能，本篇将全方位的介绍文生图板块。

> 以下内容基于 [WebUI v1.6.0](https://github.com/AUTOMATIC1111/stable-diffusion-webui/commit/5ef669de080814067961f28357256e8fe27544f4) + [中文插件](https://github.com/VinsonLaro/stable-diffusion-webui-chinese) 作为演示

## 功能分区

![](/img/post/2023.09.03/1.png)

文生图页面，按我的理解，我把它分成了四大功能区域，如上图所示，下面将详细介绍每个区域的功能和使用方法

### 快捷设置区

这个区域默认只有一个模型选择功能，可以通过 `设置 -> 用户界面 -> 快捷设置列表` 进行修改

### 提示词区

- 提示词填写区域

- 提示词快捷操作区

- 生成按钮

### 图片预览区

图片预览下面的图标所对应的功能分别是：

- 打开图片所在目录
- 保存图片
- 保存图片并打包成 Zip
- 发送图片到图生图页面
- 发送图片到图生图的局部绘制页面
- 发送图片到高清化页面

### 绘制参数区

#### 生成选项卡

- 采样步设置

- 采样器设置

- 图片尺寸设置

- 生成次数设置

- 提示词引导系数设置

- 图像生成种子设置

- 插件区

- 脚本区

#### 模型选项卡

- Embedding 模型
- HyperNetwoks 模型
- Checkpoints 模型 (基础模型)
- LoRA 模型

## 总结
