# $\delta$函数

## delta函数的定义

## delta函数的基本运算规则

delta函数和常数C的乘积

平移变换

放大，缩小性质
$$
\int^\infin_{-\infin}f(x)\delta(\alpha x)dx=\int^\infin_{-\infin}(t/\alpha)\delta(t)dt/|\alpha|=\frac{a}{|\alpha|}f(0)
$$
求导规则
$$
\int^\infin_{-\infin}f(x)\delta'(x)dx=-f'(0)
$$

$$
\int^\infin_{-\infin}f(x)\delta^{(n)}(x)dx=(-)^nf^{(n)}(0)
$$

delta函数与普通函数的乘积

常用的结果
$$
x\delta(x)=0
$$


delta函数还可以表示为初等函数的微商
$$
\int^x_{-\infin}\delta(x)=\eta(x)（在0处没有定义）
$$


拉普拉斯变换
$$
\delta(t-t_0)=\int_0^\infin\delta(t-t_0)e^{-pt}dt=e^{-pt_0}
$$
傅里叶积分
$$
\delta(x)=\frac{1}{2\pi}\int e^{ikx}dk
$$


