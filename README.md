# 来自TWT BCI Group（脑电编解码方向）的一份指南
## 0、引言

**脑机接口**（Brain Computer Interface, BCI）是神经工程学下一类较为宽泛的研究方向。广义的BCI可以泛指人脑与外界机器通过脑电信号编解码及各类神经调控技术来进行人机交互的一切途径，是人机交互的全新链路，也是各类“意念控制”技术的基础。
脑机接口的研究方向过于广泛，在采集方式上BCI可以分为侵入式脑机接口与非侵入式脑机接口，在信息流向上BCI可以分为信号编解码技术与神经调控技术。随着时代的发展围绕着脑机接口技术还诞生了包括神经心理学、神经工效学和计算神经学在内的多门学科。但无论技术如何发展迭代，脑电信号的采集及处理永远是脑机接口领域研究的基本，因此本学习指南主要面向脑电编解码方向为大家提供一个入门的指引，希望可以帮到大家快速入门脑机领域。

**Author**: YunQ
**Created Time**:  2024.08.29
**Email**: yongqi_du21@tju.edu.cn
**Version**： 1.0

## 1、前置知识

- 神经电生理基础
- 信号处理
- 微积分
- 线性代数
- 概率论与数理统计
- 编程语言（Matlab or Python）

## 2、课程设置

### Chapter 0 基础知识

- **代码基础篇**：
- **数学基础篇**：
- **ML&DL基础篇**：参照AI组ML及DL培训
- **信号基础篇**：——主要掌握概念
  - 模拟信号：
    - 信号与系统概述
    - 连续系统的时域分析
    - 傅里叶变换和系统的频域分析
  - 数字信号：
    - 采样定理与离散信号的频域分析（z变换）
  - 随机信号：*
    - 随机信号的概念及特点
    - 随机信号的统计特征
- **生理基础篇**：
  - 神经系统的组成、结构及信息传导：
    - 脑的解剖结构及生理功能
    - 神经元及胶质细胞
    - 神经元之间的信息传递
    - 神经递质及受体系统

### Chapter 1 神经电信号检测及分析

- **检测篇**：
  - 脑电的起源及测量：
    - 微电极神经系统检测
    - 大脑神经电信号检测
  - 脑电实验设计*
- **预处理篇**：
  - 脑电、诱发电位和事件相关电位
  - 脑电数据的预处理及降噪
- **分析算法篇**：
  - 时频分析
  - 盲源分离
  - 源分析
  - 复杂脑网络
- **实战应用篇**：
  - 事件相关脑电分析
  - 峰电位检测与处理
  - 局部场电位分析

### Chapter 2 机器学习与深度学习

- **机器学习篇**：
  - 机器学习分析的脑电特征
  - 脑电特征选择及降维
  - 机器学习分析示例
- **深度学习篇**：
  - 深度学习模型
  - 深度学习分析示例
- **实战篇**：
  - kaggle竞赛
  - 世界机器人大赛竞赛

### Chapter 3 数据分析工具箱

- 工具箱简介、下载及安装
- 单被试及多被试分析示例
- 绘图及批处理
