# 项目介绍

![Alt](https://repobeats.axiom.co/api/embed/1b81d2577f36a09f53a1f9216390ff64eeed8116.svg "Repobeats analytics image")



## 涉及的问题

1、当面对带有时间序列的多组数据进行聚类问题时。

2、首先尝试：提取时间序列的统计学特征值，例如最大值，最小值等。

然后利目前常用的算法根据提取的特征进行分类，例如`Naive Bayes`, `SVMs`，`KNN` 等。

但是效果并不好。

3、然后可以尝试基于`K-means`的无监督形式分类。

这种分类方式基于两个数据的距离进行分类。

需要先定义好`距离`的概念，因为是时间序列数据，考虑使用动态时间规整（Dynamic Time Warping，`DTW`）。

这部分介绍见文件夹`doc`里的原理说明文档。

<<<<<<< HEAD
本代码库，主要讲解聚类算法，包括`kmean`、 `DTW`、 `NMF`、 `infomap`等算法。
=======
### 二、数据处理

实例数据在`data`文件夹里，是一个`excel`表格，`CSV`格式。

具体是`43`个患者，连续`30`天的白细胞计数的测量结果。所以共`1290`行数据。

数据样式是：

| num  | days | WBC  |
| ---- | ---- | ---- |
| ---- | ---- | ---- |

分别代表：患者编号，哪天，以及当天测量结果。

`python`代码在文件夹`src`。为了便于调试，同时提供 `python` 脚本 和 `jupyterlab ipynb` 文件。

算法原理见`doc/chapter01.md`和`doc/chapter02.md`，具体示例的实现说明见`doc/chapter03.md`。
>>>>>>> 25544b9bcff320099ee38591324a717461810e6d

\<END>
