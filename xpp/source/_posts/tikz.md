---
title: LaTeX Tikz 基本用法
author: xpp
language: zh-CN
date: 2022-10-22 16:58:23
index_img: /img/tikz/banner.jpg
banner_img: /img/tikz/banner.jpg
excerpt: LaTeX Tikz 基本用法
categories: LaTeX
tags: [LaTeX,Tikz]
---

## 初识Tikz

### 什么是Tikz？

Tikz是LaTeX自带的绘图库，可以绘制很多样式的图，包括流程图、基本的函数、或者是一些图形（飞机等）。

- 优点：免费、开源、自由化高、灵活性强、库内的插件多
- 缺点：初始学习成本高、代码绘图不具有实时性、需要一定的数学基础（高中水平）

对于Tikz的使用，有两个核心点：

- 整体性：需要对构图有整体的理解、对构图有自己的理解，进行分片绘图

- 解析化：需要将图片转换为坐标系内的点坐标，包含旋转、平移等

当然，部分流程图不需要解析化图片，只需要按一定的逻辑写即可。

### Tikz的小例子

下面以一个例子来对Tikz的使用有一个整体的把握，具体的解析化如何实现会在后面中记录。

![Tikz 小例子](../img/tikz/Ex.pdf)



首先对这个图片需要分解为两个部分：旋转的部分和非旋转的部分，即

![非旋转部分](../img/tikz/Ex-1.pdf)![旋转部分](../img/tikz/Ex-2.pdf)

非旋转部分就很简单：就是两个箭头（坐标系）和一个箭头圆弧组成。

下面再来对旋转部分进行分析。首先去掉旋转角，可以得到

![去掉旋转](../img/tikz/Ex-2-1.pdf)

这个图形主要由三个部分组成：一条曲线、一堆箭头、和一个组合图形（飞机），即

![一条曲线](../img/tikz/Ex-2-2.pdf)![一堆箭头](../img/tikz/Ex-2-3.pdf)![一个组合图形（飞机）](../img/tikz/Ex-2-4.pdf)

最后，分析组合图形的结构：轴对称图形、两个椭圆、一个圆以及一些直线组成。

那么，图形的构图可以分析为：组合图形绘制→箭头绘制→曲线绘制→旋转一定角度→绘制坐标轴→绘制圆弧箭头。接下来就可以分片绘制了，具体细节在下面的几个章节会进行详细讲解（椭圆、圆、旋转、平移、曲线等）。

那么接下来就是Tikz的基本使用的介绍啦~

## Tikz的基本结构

### 宏包及扩展

```latex
\usepackage{tikz} % 这个就是主宏包啦ヽ(*￣▽￣*)ノ
\usetikzlibrary{shapes.geometric} % 这个是用于选取形状定位的tikz扩展
\usetikzlibrary{arrows} % 这个是箭头形式的tikz扩展，有很多定义好的箭头可以直接用
\usetikzlibrary{arrows.meta} % 这个是自定义箭头的tikz扩展
\usetikzlibrary{calc} % 这个是坐标运算的tikz扩展
\usetikzlibrary{intersections} % 这个是用于求取两个路径之间的交点的tikz扩展
\usetikzlibrary{through,hobby} % 常用曲线的tikz扩展
\usetikzlibrary{patterns} % 填充形状的tikz扩展
```

### Tikz环境

```latex
\begin{tikzpicture}[%环境内tikz的全局设置放在这个中括号内%]
% 可以在这里愉快的画图啦
\end{tikzpicture}
```



## Tikz基本语法



