# 强化学习
## 训练机器人走迷宫

### 项目概述及目的

![img.png](default.png)

在该项目中，将使用强化学习算法，实现一个自动走迷宫机器人。

1. 如上图所示，智能机器人显示在右上角。在我们的迷宫中，有陷阱（红色炸弹）及终点（蓝色的目标点）两种情景。机器人要尽量避开陷阱、尽快到达目的地。
2. 机器人可执行的动作包括：向上走 `u`、向右走 `r`、向下走 `d`、向左走 `l`。
3. 执行不同的动作后，根据不同的情况会获得不同的奖励，具体而言，有以下几种情况。
    - 撞到墙壁：-10
    - 走到终点：50
    - 走到陷阱：-30
    - 其余情况：-0.1
4. 我们需要通过修改 `robot.py` 中的代码，来实现一个 Q Learning 机器人，实现上述的目标。

###  配置环境，软件及库的安装
使用 `envirnment.yml` 文件配置名为 `robot-env` 的 conda 环境，具体而言，需转到当前的目录，在命令行/终端中运行如下代码，稍作等待即可。
```
conda env create -f environment.yml
```
安装完毕后，在命令行/终端中运行 `source activate robot-env`（Mac/Linux 系统）或 `activate robot-env`（Windows 系统）激活该环境。

###文件描述
- robot_maze.ipynb: 主要的代码实现和分析文件
- Robot.py: 主要的python代码实现文件
- Maze.py: 补充的python代码实现文件
- Runner.py: 补充的python代码实现文件
- environment.yml: 环境配置文件
- image文件夹: 迷宫的构建图片
- default: 迷宫的示例图片
- default2: 迷宫的示例图片
- README.md

