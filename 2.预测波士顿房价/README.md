# 模型评估与验证
## 波士顿房价预测

### 项目概述及目标

经过编辑的波士顿房价数据集有490个数据点，每个点有三个特征。这个数据集编辑自[加州大学欧文分校机器学习数据集库（数据集已下线）](https://archive.ics.uci.edu/ml/datasets.html)。项目任务是：

### 项目方法及步骤

- 分析数据进行基础统计运算和特征工程，了解数据集
- 数据的分割，使用决策树算法训练模型，进行数据拟合
- 通过网格搜索和交叉验证，优化模型，并作出价格预测
- 分析决定系数，模型的鲁棒性及应用范围

### 软件和库的安装

这个项目需要安装 **Python3** 和以下的 Python 函数库：

- [NumPy](http://www.numpy.org/):数值计算
- [matplotlib](http://matplotlib.org/): 用于画图
- [scikit-learn](http://scikit-learn.org/stable/): 用于模型训练和分析

### 数据集

**特征**

1. `RM`: 住宅平均房间数量
2. `LSTAT`: 区域中被认为是低收入阶层的比率
3. `PTRATIO`: 镇上学生与教师数量比例

**目标变量**

`MEDV`: 房屋的中值价格

### 文件描述

- boston_housing.ipynb: 完整的代码和分析文件
- housing.csv: 数据集
- visuals.py: python可视化文件
- README.md
