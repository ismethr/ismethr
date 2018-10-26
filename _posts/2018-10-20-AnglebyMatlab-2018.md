---
layout:     post                    # 使用的布局（不需要改）
title:      利用 Matlab 计算各种角度               # 标题 
subtitle:   几何的世界你永远不懂 #副标题
date:       2018-10-19              # 时间
author:     文叨                      # 作者
header-img: img/post-bg-universe.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - Matlab
    - Paper
    - Point Cloud
---

## 各种（空间）角度的计算方法
>以前自己的立体几何学的不好，各种计算方法全都忘记的差不多了，在这里整理与总结一下，便于以后查询和分享吧

 **1.两向量间夹角**
>Calculate the 3D angle between two vectors

The angle between two three-element vectors, P1 and P2, can be calculated using matlab in the following way:
<p>a = atan2(norm(cross(P1,P2)),dot(P1,P2)); % Angle in radians</p>



The angle will lie between 0 and pi radians. To get degrees use ‘atan2d’.

Note: However, the cosine of such an angle can be calculated as:

cosine of the angle = dot(P1,P2)/(norm(P1)*norm(P2))
No need to compute the angle itself.
 

