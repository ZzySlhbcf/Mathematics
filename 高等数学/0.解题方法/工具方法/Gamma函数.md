## $\Gamma$函数

[[反常积分]]

$$\Gamma(1)=1\quad\Gamma(1/2)=\sqrt{\pi}\qquad\Gamma(5/2)=3/2\cdot1/2\cdot\Gamma(1/2)=3\sqrt{\pi}/4$$


若$e^{-x^2}$

$$\Gamma(a)=\int^{+\infty}_0x ^{a-1}e^{-x}\mathrm{d}x\xlongequal{x=t^2}2\int^{+\infty}_0t^{2a-1}e^{-t^2}\mathrm{d}t$$

若$e^{-x}$
$$\begin{align}\Gamma(\alpha+1)=\int^{+\infty}_0x^{\alpha}e^{-x}\mathrm{d}x=\alpha\Gamma(\alpha)\\\Gamma(n+1)=n!\end{align}$$
### $\Gamma$函数的定义域

1. $a-1\geqslant0$ 收敛
2. $a-1<0$ a>0时收敛

# 快速记忆

1. 整数阶乘终点为$0\to{0}!=1$
2. 分数阶乘终点为$-\frac{1}{2}\to\left( -\frac{1}{2} \right)!=\sqrt{ \pi }$

$$
\int^{+\infty}_{0}x^\alpha e^{-x}\mathrm{d}x=(\alpha)!
$$
$x$的次数是几, 结果就是几的阶乘

$$
\int^{+\infty}_{0}x^\alpha e^{-x^2}\mathrm{d}x=\frac{1}{2}\int^{+\infty}_{0}x^{\alpha-1}e^{-x^2}\mathrm{d}(x^2)=\frac{1}{2}\int^{+\infty}_{0}(x^2)^{\alpha-1\over_{2}}e^{-x^2}\mathrm{d}(x^2)=\frac{1}{2}\left(\frac{\alpha-1}{2} \right)!
$$