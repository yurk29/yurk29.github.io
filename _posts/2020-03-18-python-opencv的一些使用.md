---
layout: post
title: python中opecv模块的一些简单使用
subtitle: 简单用法
date: 2020-03-18
author: zz
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    -python
    -opencv
---

## 安装opencv

在anaconda里面搜索opencv模块安装

## 使用opencv模块

    import cv2  # 导入opencv模块，注意是cv2
    img = cv2.imread("D:\\img.jpg")  # 读取D:\img.jpg
    cv2.imshow("demo", img)  # 将img以demo窗口名展示
    cv2.waitKey()  # 如果无输入则窗口一直存在
    cv2.destroyWindow("demo")  # 关闭demo窗口
