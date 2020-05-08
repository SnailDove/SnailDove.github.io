---
title: 《Spark权威指南》的翻译综述
date: 2020-02-10
copyright: true
categories: 中文
tags: [Spark]
mathjax: false
mathjax2: false
toc: true
top: 12
---

<img src="http://q9kvrafcq.bkt.clouddn.com/SparkTheDefinitiveGuide/Spark权威指南封面.jpg" alt="1" style="zoom:68%;"/>

### 前言

本系列文章将对《Spark - The Definitive Guide - Big data processing made simple》进行翻译，参照其他译本，取名为：《Spark权威指南》，翻译工作全程由我个人独自翻译，属于对照式翻译，有助于读者理解，如有不当或错误之处，欢迎不吝指出，方便你我他。

### 本书英文版出版信息

2018年2月第一版

![image-20200212161419538](http://q9kvrafcq.bkt.clouddn.com/SparkTheDefinitiveGuide//image-20200212161419538.png)

### **翻译进度**

Part I. Gentle Overview of Big Data and Spark

- <a href="https://snaildove.github.io/2019/11/07/Chapter3_A-Tour-of-Spark-Toolset(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第3章：Spark工具一览</a>

Part II. Structured APIs—DataFrames, SQL, and Datasets

- <a href="https://snaildove.github.io/2019/08/05/Chapter4_StructuredAPIOverview(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第4章：结构化API概览</a>
- <a href="https://snaildove.github.io/2019/08/05/Chapter5_Basic-Structured-Operations(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第5章：基本结构化的操作</a>
- <a href="https://snaildove.github.io/2019/08/05/Chapter6_Working-with-Different-Types-of-Data(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第6章：处理不同的数据类型</a>
- <a href="https://snaildove.github.io/2019/08/05/Chapter7_Aggregations(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第7章：聚合</a>
- <a href="https://snaildove.github.io/2019/08/05/Chapter8-Joins(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第8章：连接</a>
- <a href="https://snaildove.github.io/2019/10/20/Chapter9_DataSources(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第9章：数据源</a>
- <a href="https://snaildove.github.io/2019/10/20/Chapter10_Spark-SQL(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第10章：Spark SQL</a>
- <a href="https://snaildove.github.io/2019/11/07/Chapter11_DataSets(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第11章：Dataset</a>

Part III. Low-Level APIs

- <a href="https://snaildove.github.io/2019/11/07/Chapter12_Resilient-Distributed-Datasets-(RDDs)(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第12章：RDD</a>
- <a href="https://snaildove.github.io/2019/11/07/Chapter13_Advanced-RDDs(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第13章：高级RDD</a>
- <a href="https://snaildove.github.io/2019/11/07/Chapter14_Distributed-Shared-Variables(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第14章：分布式共享变量</a>

Part IV. Production Application

- <a href="https://snaildove.github.io/2019/08/05/Chapter15_HowSparkRuns-on-a-Cluster(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第15章：Spark如何在集群上的运行</a>
- <a href="https://snaildove.github.io/2019/08/05/Chapter16_DevelopingSparkApplications(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第16章：开发Spark应用程序</a>
- <a href="https://snaildove.github.io/2019/08/07/Chapter17_Deploying-Spark(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第17章：部署Spark应用程序</a>
- <a href="https://snaildove.github.io/2019/08/10/Chapter18_Monitoring-and-Debugging(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第18章：监控和调试</a>
- <a href="https://snaildove.github.io/2019/08/13/Chapter19_Performance-Tuning(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第19章：性能调优</a>

Part V. Streaming

- <a href="https://snaildove.github.io/2019/06/02/Chapter20_StreamProcessingFundamentals(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第20章：流处理基础</a>
- <a href="https://snaildove.github.io/2019/06/28/Chapter21_StructuredStreamingBasics(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》 第21章 结构化流基础</a>
- <a href="https://snaildove.github.io/2019/07/28/Chapter22_EventTimeAndStatefulProcessing(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第22章：事件时间和状态处理</a>
- <a href="https://snaildove.github.io/2019/08/10/Chapter23_StructuredStreamingInProduction(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第23章：生产环境中的结构化流</a>

Part VI. Advanced Analytics and Machine Learning

- <a href="https://snaildove.github.io/2019/08/20/Chapter24_Advanced-Analytics-and-Machine-Learning-Overview(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第24章：高级分析和机器学习概述</a>
- <a href="https://snaildove.github.io/2019/08/26/Chapter25_PreprocessingAndFeature(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第25章：预处理与特征工程</a>
- <a href="https://snaildove.github.io/2019/09/01/Chapter26_Classification(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第26章：分类</a>
- <a href="https://snaildove.github.io/2019/09/01/Chapter27_Regression(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第27章：回归</a>
- <a href="https://snaildove.github.io/2019/08/31/Chapter28_Recommendation(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第28章：推荐</a>
- <a href="https://snaildove.github.io/2019/08/05/Chapter29-Unsupervised-Learning(SparkTheDefinitiveGuide)_online/">翻译：《Spark权威指南》第29章：无监督学习</a>

<font color="red">还有第1,2,30章未翻译，近期太忙，择日翻译。</font>

### 本书的勘误

[Errata | O'Reilly Mediawww.oreilly.com](https%3A//www.oreilly.com/catalog/errata.csp%3Fisbn%3D0636920034957)

### Last but not least

如果你觉得本系列文章对你有帮助亦或愿意对我的开源付出进行支持，可以对我的本系列文章打赏，毕竟开源不易，由衷感谢你的关注与支持！！！

