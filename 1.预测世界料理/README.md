# 机器学习工程师纳米学位
## 预测下一道世界料理

### 项目概述及目标

此项目的数据集来自[Kaggle What's Cooking](https://www.kaggle.com/c/whats-cooking/data) 竞赛，共 39774/9944 个训练和测试数据点，涵盖了中国菜、越南菜、法国菜等的信息。项目任务是：给定佐料名称，预测菜品所属的菜系。

### 项目步骤

- 菜品数据载入
- 佐料名称预处理，并预览数据集结构，包括自然语言处理（NLP）的技术应用
- 载入逻辑回归模型，并训练并测试训练结果

### 软件和库的安装

这个项目需要安装 **Python3** 和以下的 Python 函数库：

- [Pandas](https://pandas.pydata.org/)
- [NumPy](http://www.numpy.org/):数值计算
- [matplotlib](http://matplotlib.org/): 用于画图
- [nltk](https://www.nltk.org/): 用于处理单词文本
- [scikit-learn](http://scikit-learn.org/stable/): 用于模型训练和分析
- [jupyter,notebook](http://jupyter.org/): 实验基本环境，以运行和编辑 `.ipynb`

```bash
pip install pandas numpy matplotlib nltk scikit-learn jupyter notebook
python -c "import nltk; nltk.download('wordnet')"
```

### 数据集

数据集来自[Kaggle What's Cooking](https://www.kaggle.com/c/whats-cooking/data) 竞赛，共 39774/9944 个训练和测试数据点，涵盖了中国菜、越南菜、法国菜等的信息。

**特征**

1. `id`: 数据编号，例如, "24717".
2. `ingredients`: 此菜所包含的原料，例如["tumeric", "vegetable stock", ...] 

**目标变量**

`cuisine`: 菜名，例如, "indian".

### 文件描述

- PredictYourCuisine.ipynb: 完整的代码文件
- train.json: 从Kaggle下载的训练集
- test.json: 从Kaggle下载的测试集
- README.md