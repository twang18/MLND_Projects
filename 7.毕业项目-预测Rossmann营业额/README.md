# 机器学习工程师纳米学位

# 毕业项目

## 预测Rossmann营业额

### 项目概述及目的
本项目是来自[Kaggle](https://www.kaggle.com/c/rossmann-store-sales#description)的一个竞赛项目。Rossmann药妆店在欧洲的7个国家里有3000多家连锁店。影响药妆店的营业额的因素很多，比如打折，附近的竞争者，学校假期（寒暑假），国家假期（圣诞节），季节性和本地因素，药店规模和类型，药店装修歇业等等。这些因素都让每家药店的营业额各不相同。

为了药妆店更好的运营，Rossmann试图找到影响药店营业额的多种因素的潜在模型，从而更好地预测药店的营业额。在本项目中，Rossmann提供的数据集包含全德国1115家店的1017209条数据，时间周期是从2013年1月1日到2015年7月31日止，这31个月的数据。要预测的对这1115家店，从2015年8月1日到2015年9月17日共六周的营业额。

### 项目方法及步骤

- 数据集预处理&特征构建
- 可视化&探索性数据处理EDA&特征选择
- 算法选择及建模: 最终选择了xgboost的算法
- 训练模型
- 对训练模型的可视化及参数优化
- 对模型的讨论

###  软件及库

- pandas, numpy, matplotlib, seaborn, sklearn, scipy, xgboost
- python version: 3.6


###文件描述
- Rossmann Sales.ipynb: 完整的数据挖掘，预处理，分析及建模的文件
- Project Proposal_Rossmann.pdf: 开题报告
- Rossmann Sales Project Report.pdf: 项目报告
- 三个数据集：store.csv, train.csv, test.csv
- README.md

