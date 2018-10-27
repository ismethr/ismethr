---
layout:     post                    # 使用的布局（不需要改）
title:      Report @ 10/29/2018              # 标题 
subtitle:   study for share #副标题
date:       2018-10-27              # 时间
author:     Wen Dao                      # 作者
header-img: img/post-bg-rwd.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - report
    - 汇报
    - keynote
    
---
## 点云主方向的计算
> 在微分几何中，在曲面给定点的两个主曲率（principal curvatures）衡量了在给定点一个曲面在这一点的不同方向怎样不同弯曲的程度。在三维欧几里得空间中可微曲面的每一点 *p*，可选取一个单位**法向量**。在 *p* 的一个法平面是包含该法向量以及与曲面相切的惟一一个方向的平面，在曲面上割出一条平面曲线。这条曲线在 *p* 的不同法平面上一般有不同曲率。在 *p* 的主曲率，记作 *k<sub>1</sub>* 与 *k<sub>2</sub>*，是这些曲率的最大与最小值。这里一条曲线的曲率由定义是密切圆半径的倒数。当曲线转向与平面给定法向量相同方向时，曲率取正值，否则取负值。当曲率取最大与最小值的两个法平面方向总是垂直的，这是欧拉在1760年的一个结论，称之为**主方向**。  ———— [维基百科](https://zh.wikipedia.org/wiki/%E4%B8%BB%E6%9B%B2%E7%8E%87)

![Courbure-dun-objet-3D-a-Principe-de-mesure-de-la-courbure-b-Courbure-moyenne.png](https://i.loli.net/2018/10/27/5bd3d05b9a26c.png)  

### 法向量
>法向量是空间解析几何的一个概念，垂直于平面的直线所表示的向量为该平面的法向量。由于空间内有无数个直线垂直于已知平面，因此一个平面都存在无数个法向量（包括两个单位法向量）。  

- 法向量的计算方法


