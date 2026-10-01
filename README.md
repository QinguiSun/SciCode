
<p align="center">
  <img src="https://raw.githubusercontent.com/QinguiSun/SciCode/main/SciCode.png" alt="SciCode" width="320">
</p>

<p align="center">
  <strong>面向 AI4Materials，学习“科学编程”</strong><br>
  训练 Python 技能，同时理解材料科学问题。
</p>

---

## 关于 SciCode（闪扣）


**SciCode（闪扣）** 是一个面向 **AI4Materials** 的科学编程练习项目。

它不仅关注“代码能不能写出来”，也关注：

- 这个问题在材料科学中意味着什么？
- 晶格、周期性边界、原子结构应该如何用代码表示？
- 掺杂、点缺陷、晶体图等对象应该如何构造与处理？
- Python、科学计算与机器学习如何真正进入材料研究流程？

SciCode 希望把 **编程训练** 与 **材料科学问题理解** 放在同一套练习中，让学习者从基础 Python 逐步进入真实的 AI4Materials 任务。

---

## 学习目标

通过 SciCode，你将逐步训练以下能力：

- **Python 编程基础**
  - 变量、条件判断、循环、函数
  - 列表、字典、集合
  - NumPy 与科学计算
  - 数据处理与算法思维

- **材料科学中的结构表示**
  - 原子与元素
  - 晶格与晶胞
  - 分数坐标与笛卡尔坐标
  - 周期性边界条件（PBC）
  - 邻居搜索与截断半径

- **晶体结构操作**
  - 超胞构建
  - 掺杂
  - 空位与点缺陷
  - 原子替换
  - 周期体系中的距离计算

- **AI4Materials 基础**
  - 晶体数据处理
  - 大规模 DFT 数据集
  - 高通量筛选
  - 材料性质预测
  - 晶体生成
  - 3D Graph Neural Networks
  - Uncertainty Quantification

---

## SciCode 的特点

### 1. 从编程题进入材料科学

传统编程练习往往围绕字符串、数组和抽象算法展开。

SciCode 尝试进一步提出：

> 如果数组中的数字变成原子坐标呢？  
> 如果图结构变成晶体结构呢？  
> 如果“边界条件”变成周期性边界条件呢？

在练习 Python 的同时，也逐步建立材料计算中的基本直觉。

### 2. 面向真实的 AI4Materials 工作流

SciCode 中的题目将尽量靠近实际任务，例如：

```text
晶体结构
   ↓
结构解析 / 清洗
   ↓
周期性邻居搜索
   ↓
特征与图构建
   ↓
机器学习模型
   ↓
性质预测 / 高通量筛选 / 晶体生成
```

### 3. 从零编程基础开始

SciCode 不要求学习者已经具备系统的计算机背景。

课程将从基础 Python 开始，逐渐过渡到科学计算、材料数据以及机器学习相关任务。

---

## 题库规模

SciCode 计划包含：

> **100 道科学编程练习**

题目将按照难度逐步推进，从 Python 基础一直延伸到 AI4Materials 中的典型计算问题。

一个可能的学习路径是：

```text
Python
  ↓
NumPy / Scientific Computing
  ↓
Atoms & Coordinates
  ↓
Crystal Lattice
  ↓
Periodic Boundary Conditions
  ↓
Doping & Point Defects
  ↓
Crystal Graph
  ↓
3D GNN
  ↓
AI4Materials Applications
```

---

## 适合谁？

SciCode 主要面向：

- 材料科学、物理、化学等背景的学生与研究者
- 希望学习 Python 的材料研究者
- 对科学编程（Scientific Programming）感兴趣的学习者
- 希望进入 AI4Materials / Materials Informatics / Scientific Machine Learning 的学习者
- 希望理解 3D GNN、晶体机器学习和材料生成模型基础的人

---

## 为什么是“科学编程”？

编程能力并不只是掌握一门语言。

在科学研究中，更重要的问题往往是：

> **如何把科学对象、物理约束和研究问题转化成可以计算的形式？**

例如：

```python
# 普通编程问题
distance = abs(x1 - x2)
```

对于周期晶体，同一个问题可能变成：

```python
# Scientific Programming
# 两个原子之间的距离需要考虑 Periodic Boundary Conditions
```

因此，SciCode 希望训练的不只是 Python 语法，而是：

**Python + Scientific Thinking + Materials Problems**

---

## 项目愿景

SciCode 希望成为一个面向 AI4Materials 的开放科学编程练习库。

我们希望学习者能够通过一系列小而具体的编程问题，逐步理解：

**如何让代码表示原子、理解晶体，并最终参与材料的预测、筛选与生成。**

---

## Repository

课程图片：

[SciCode.png](https://github.com/QinguiSun/SciCode/blob/main/SciCode.png "SciCode.png")

Repository：

`QinguiSun/SciCode`

---

## License

如无特别说明，本项目内容采用：

**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International  
(CC BY-NC-SA 4.0)**

进行许可。

---

## Contact

如果你发现问题、有新的题目建议，或者希望参与 SciCode 的建设，欢迎联系：

**Qingui Sun（孙钦贵）**

Email: `kinguinsun@gmail.com`

---

<p align="center">
  <strong>SciCode · Learn to code. Learn to understand materials.</strong>
</p>
