# 模型介绍

$$\left( \sum{k=1}^n a_k b_k \right)^2 \leq \left( \sum{k=1}^n ak^2 \right) \left( \sum{k=1}^n b_k^2 \right)$$


$`\sqrt{3x-1}+(1+x)^2`$

![dddd](https://github.com/facegy/Jason-Gao-Public/edit/main/1.png)

$\sqrt{3x-1}+(1+x)^2$


$`\sqrt{3x-1}+(1+x)^2`$


```math
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$



$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$


$yi = xi^′β + εi  (i=1,⋯,n) \\ \\ β 的一致估计要求 Cov (xi,εi) = 0$


**拟合值大于1或者小于0，不符合现实（通过使用Logit/Probit/Tobit 模型解决）。**


因为二元变量（0 或者 1 ）一般度量的是概率，概率只能取值 [0，1]。


---

**LPM的边际效应是常数（通过使用Logit/Probit/Tobit 模型解决）。**

自变量增加1单位的影响是相同的，比如在研究妇女就业决定的时候，妇女养育的孩子数量从0个上升到1个，与1个上升到 2 个，对就业的影响是一样的。

**LPM 内生性问题**

由于 $*ε_i = y_i − xi^′\beta*$ , 故 $ε_i = 1 − xi^′\beta$ 或 $ε_i = − xi^′\beta$， 因此 $*\epsilon_i$* 必然与 $*x_i$* 相关, 导致估计不一致。

**异方差问题（通过计算“异方差稳健标准误”解决）**

 $*\epsilon_i$* 从两点分布, 而非正态分布。而且由于 $Var (ε_i) = Var (x_i^{'} \beta)$ 故扰动项 $*\epsilon_i$* 的方差依赖于 $*x_i$* 存在异方差（故应使用稳健标准误）。

$$
Var(εi) = Var（0 − xi^′\beta） = Var（xi^′\beta） = p(x)[1−p(x)]
$$

其中，$*p(x) = β0 + β_1x_1 + β_2x_2 + … + \beta_nx_n*$








