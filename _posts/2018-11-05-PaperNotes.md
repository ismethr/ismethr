---
layout:     post                    # 使用的布局（不需要改）
title:      枝叶点云分割 —— 论文             # 标题 
subtitle:   An automated approach for wood-leaf separation from terrestrial LIDAR point clouds using the density based clustering algorithm DBSCAN —— 论文翻译及总结 #副标题
date:       2018-11-05              # 时间
author:     Wen Dao                      # 作者
header-img: img/post-bg-xq.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - Point Cloud
    - Paper
    - Terrestrial Laser Scanner
    
---

> 让人头疼的毕业论文，不过还是要一步一步的来。重点内容翻译，并不是整篇文章的译文  

## 题目：基于密度的聚类算法DBSCAN从地面LIDAR点云分离木叶的自动方法  
> Ferrara R, Virdis S G P, Ventura A, et al. An automated approach for wood-leaf separation from terrestrial LIDAR point clouds using the density based clustering algorithm DBSCAN[J]. Agricultural and Forest Meteorology, 2018.  

### 1. 引言  
　　森林空间结构信息和树木几何形态地精确重建可广泛应用于多种空间尺度上多种森林环境应用中（生态系统生产力模型，碳动态和生态研究，森林管理，疾病和压力检测，燃料特性描述等）。多种遥感技术应用于不同空间尺度的森林结构研究，其中地基激光雷达可以获取较为详细的森林内部结构信息，在森林结构领域研究具有丰富的应用前景。
> The general aim of this study is thus to evaluate the potential of TLS in direct sampling and automatic quantification of stems, branches, and canopy for broad leaved non-deciduous trees following an automated processing flow and using an unsupervised clustering approach. Specific objectives were: i) to set up a multi-scan voxel-based procedure for automated wood/non-wood separation under leaf-on conditions using a Density-Based Spatial Clustering algorithm, and ii) to evaluate performance, quality and drawbacks of the proposed procedure.  

因此，本研究的主要目的是评估TLS在自动处理流程和使用无监督聚类方法后对阔叶非落叶树的茎，枝和冠的直接采样和自动定量的潜力。 具体目标是：1）使用基于密度的空间聚类算法，在叶子条件下建立基于多扫描体素的自动木材/非木材分离程序；2）评估性能，质量和缺点及后续改进。  

