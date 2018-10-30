---
layout:     post                    # 使用的布局（不需要改）
title:      森林空间结构              # 标题 
subtitle:   用一些参数描述森林在空间尺度上的分布 #副标题
date:       2018-10-22              # 时间
author:     文叨                      # 作者
header-img: img/post-bg-forest-1.jpg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - 森林
    - 空间结构
    - 论文
    - Forest stand structure
---

>文章主要参考：柴宗政. 基于相邻木关系的森林空间结构量化评价及R语言编程实现[D]. 西北农林科技大学, 2016.

## 森林结构量化表达

![森林结构特征及量化评价比较.png](https://i.loli.net/2018/10/22/5bcda4754fb3c.png)

### 林分结构  
　　林分结构是指林分内林木群体特性的空间分布格局，包括物种结构、林分水平结构及林分垂直结构等。

### 林分密度
>陈东来, 刘丽华, 张景兰. 林分密度的新指标--冠积指数[J]. 东北林业大学学报, 2003, 31(5):15-17.  

　　林分密度 (Stand density) 是指单位面积林地上的林木数量，反映了林分内林木对其所占有空间的利用程度，显著影响着林分生长、木材产量及质量

### 空间结构均质性指数  

　　[李建军](http://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFD2013&filename=STXB201312020&uid=WEEvREcwSlJHSldRa1FhdXNXa0d1REoxYnNLSGhuRXVGUlNob2lzS0V4UT0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MDg4MjJuVGJMRzRIOUxOclk5SFpJUjhlWDFMdXhZUzdEaDFUM3FUcldNMUZyQ1VSTEtlWitSdEZ5RGhWTDNKTmo=) (2013) 借鉴林分择伐空间结构优化模型，从生态学有关生态系统内部均衡和均质原理，在生态系统(斑块尺度)，从空间结构的混交(混交度和大小比数)、竞争(竞争指数)、空间分布格局(角尺度、空间密度指数及林层指数)3 个方面提出基于Voronoi 图的空间结构均质性指数。
>李建军, 刘帅, 张会儒, 等. 洞庭湖森林生态系统空间结构均质性评价[J]. 生态学报, 2013, 33(12): 3732-3741.

### 点云数据
