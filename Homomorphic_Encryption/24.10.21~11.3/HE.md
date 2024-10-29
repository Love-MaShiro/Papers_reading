# Fully Homomorphic Encryption

# 引言
+ 同态加密定义
    密文与明文执行相同运算操作</p>

+ 分类
  1.单同态加密(Partially Ho-momorphic Encryption, PHE)
  >执行一种运算（次数无限）
  
  2.类同态加密(Somewhat Homo-morphic Encryption, SWHE)
  >支持多种运算，但是运算次数有限

  3.全同态加密(Fully Homomorphic Encryption, FHE)
  >可以支持无限次、所有种类的电路同态运算
+ 全同态加密方案介绍
# 格密码理论基础
## 格及其困难问题
### 格的定义
若格给出一组线性无关的向量$b_1$,$b_2$,$b_3$,···,$b_n\in \mathbb{R}^m$，则格L可以由$b_1$,$b_2$,$b_3$,···,$b_n$的整系数线性组合生成。
$$
L=\left\{ z_1\boldsymbol{b}_1+z_2\boldsymbol{b}_2+···+z_n\boldsymbol{b}_{\boldsymbol{n}}\ |\ z_1,z_2,z_3,···,z_n\in \mathbb{Z} \right\} 
$$
格是$\mathbb{R}^m$上的一个离散子群                                                                           
### 格上困难问题
+ 最短向量问题(SVP)
  输入格L后，发现格L的最短向量
+ 最靠近向量问题(CVP)
  输入格L与一个目标向量t，发现一个最靠近t的一个格点v


  