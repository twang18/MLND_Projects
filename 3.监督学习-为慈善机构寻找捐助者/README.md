# 监督学习 Supervised Learning
## 项目：为CharityML寻找捐献者

## 项目概述
在这个项目中，我们使用监督技术和分析能力对美国人口普查数据进行分析，以帮助CharityML（一个虚拟的慈善机构）识别最有可能向他们捐款的人。

## 项目方法及步骤
**项目采用如下探究方法及步骤：**

- 探索数据以了解人口普查数据是如何记录的
- 使用一系列的转换和预处理技术进行数据清理
- 从7种监督算法中选择了最适合该数据集的三种算法（决策树，支持向量机和集成方法）来训练模型，评估各模型的表现，从中找到最优模型
- 进一步优化选择的模型
- 探索选择的模型和它的预测能力。

**从中我可以学会以下内容：**

- 知道什么时候应该使用预处理以及如何做预处理。
- 如何为问题设置一个基准。
- 判断在一个特定的数据集上几个监督学习算法的表现如何。
- 调查候选的解决方案模型是否足够解决问题。

## 软件和库

这个项目要求使用 Python 并且需要安装下面这些python包：

- [Python](https://www.python.org/download/releases/2.7/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

## 文件描述

- find_donors.ipynb: 主要的代码和分析文件。
- census.csv: 项目使用的数据集
- visuals.py: 实现可视化功能的Python代码
- README.md
