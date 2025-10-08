---
title: Math257(Linear Algebra and its Application)
author: Haoyang
date: 2025-09-1
layout: post
mermaid: true
---

## 课程大概
1. reference link : [MIT18.06](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/){:target="_blank"}
2. 课程内容相对简单，主要分享一些Linear Algebra **题目**和**应用**，可以综合运用所学知识，具体**基础知识**可以参考MIT18.06，链接如上

### **线性代数核心知识点 (MIT 18.06 框架)**

#### **1. 方程组与矩阵基础 (Solving Ax = b)**
   
   1.1.  线性方程组的几何诠释 (行图像 vs. 列图像)

   1.2.  高斯消元法 (Gaussian Elimination) 与主元 (Pivots)

   1.3.  矩阵运算 (乘法, 转置) 与逆矩阵 ($A^{-1}$)

   1.4.  LU 分解 (LU Decomposition)


#### **2. 四大基本子空间 (The Four Fundamental Subspaces)**
   
   2.1.  向量空间 (Vector Spaces) 与子空间 (Subspaces)

   2.2.  四大基本子空间:

 1)列空间 (Column Space, $C(A)$)

 2)零空间 (Nullspace, $N(A)$)

 3)行空间 (Row Space, $C(A^T)$)

 4)左零空间 (Left Nullspace, $N(A^T)$)

   2.3.  方程组 $A\vec{x} = \vec{b}$ 的完整解 ($\vec{x} = \vec{x}_p + \vec{x}_n$)

   2.4.  线性无关 (Independence), 基 (Basis), 维度 (Dimension) 与秩 (Rank)

#### **3. 正交性与最小二乘法 (Orthogonality and Least Squares)**
   
   3.1.  正交向量与正交子空间 (Orthogonality)

   3.2.  投影 (Projections)

   3.3.  最小二乘法 (Least Squares Approximations)

   3.4.  标准正交基 (Orthonormal Bases) 与格拉姆-施密特正交化 (Gram-Schmidt)

   3.5.  QR 分解 (QR Decomposition)

#### **4. 特征值与特征向量 (Eigenvalues and Eigenvectors)**

   4.1.  特征值 ($\lambda$) 与特征向量 ($\vec{x}$) 的定义 ($A\vec{x} = \lambda\vec{x}$)

   4.2.  特征方程: $\det(A - \lambda I) = 0$

   4.3.  矩阵的对角化: $A = S\Lambda S^{-1}$

   4.4.  应用: 微分方程组, 矩阵的幂, 马尔可夫矩阵


#### **5. 高级主题与应用 (Advanced Topics)**

   5.1.  对称矩阵 (Symmetric Matrices) 与正定矩阵 (Positive Definite Matrices)

   5.2.  奇异值分解 (Singular Value Decomposition, SVD): $A = U\Sigma V^T$

   5.3.  线性变换 (Linear Transformations)
   
   5.4   主成分分析 PCA (Principal Component Analysis)

### 问题集(Problem Sets)
#### problem 1
Given three sequences {$x_n$}, {$y_n$},{$z_n$} satisfy that $x_1=-2,y_1=1,z_1=-1$, and we have $x_{n+1}=3x_n-6y_n-z_n$, &nbsp; &nbsp;  $y_{n+1}=-x_n+2y_n +z_n$ &nbsp; &nbsp;   $z_{n+1}=x_n+3y_n-z_n$, find the limit:&nbsp;  $\lim_{n\rightarrow \infty}\frac{x_n+y_n+z_n}{3^n+5^n}$

#### [problem 1: solution ](/assets/pdfs/Problem1_solution.pdf){:target="_blank"}
### 应用集(Applications)

