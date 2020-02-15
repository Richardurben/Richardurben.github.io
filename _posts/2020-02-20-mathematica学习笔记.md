---
layout: post
title: "*MATHEMATICA* 学习笔记"    #这是文章正标题
subtitle: 'software note'              #这是副标题
date:   2020-02-15                  #时间
author: GYS                         #作者
header-style: text                   #标题格式
header-img: img/holiday_delay-bg.jpg          #这篇文章标题背景图片
header-mask: "0.1"       # 博文页面上端的背景图片的亮度，数值越大越黑暗
catalog: true 						# 开启catalog，将在博文侧边展示博文的结构
istop: false            # 设为true可把文章设置为置顶文章
music-id:         # 网易云音乐单曲嵌入
music-idfull:         # 网易云音乐歌单嵌入
apserver: netease    # 音乐平台netease/tencent/kugou/xiami/baidu
aptype: playlist    # 音乐类型song/playlist/album/search/artist
apsongid: 3136773942   # 音乐song/playlist/album id
tags:
- Markdown
- Mathematica
- Music
---

> WOLFRAM *MATHEMATICA* 实用编程指南 原书第二版

> [美] 克里夫·黑斯廷斯    开尔文·米斯裘    迈克尔·莫里森著

> 北京：科学出版社，2018.6

## 特色
**自由格式: 在线关键词联想，可自动生成编程语句，依赖wolfram知识库，涵盖各个学科超过10万亿条数据**

**采用wolfram语言指令，可总结一下三项准则:**

1. wolfram 语言指令以大写字母开头,若指令由多个单词组成，则每个单词的首字母都需要大写 (triks:自定义函数可以使用小写字母以便与内置函数相区别).
2. 函数参数用方括号 **[]** 括起.
3. 列表，也用于存储定义域和范围，用花括号 **{}** 括起来.

**Example：Plot[Sin[x],{x,0,2$\pi$}]**

**可作为文字处理与排版的工具(共享文档格式为 .nb),也可以输出pdf、保存图片、共享含有计算文档(CDF)的交互文件**

**幻灯片演示**

**定义交互模型:**

~~~
**Manipulate[Plot[Sin[frequency\*x],{x,0,2$\pi$}],{frequency,1,5}]**
~~~

**代数运算和方程求解，微积分与微分方程，线性代数，概率与统计**

**数据处理(输入输出，文本，图像，声音等)**

## 总结
**可视为 *MATHEMATICA* 入门指南，较详尽概述了该软件基础应用方法以及学习路径，为初学者提供了很好的学习思路，但深度方面有些缺憾，个人感觉与MATLAB相比，应用方面甚至较弱，希望有机会能更深入了解该软件.**

## PS：
**此书手感极佳，在这个电子书横行，纸质书隐退的时代，一本入手能给人眼前一亮的书不可多的，毫不客气的说：我就是冲他颜值去的！(微笑)**