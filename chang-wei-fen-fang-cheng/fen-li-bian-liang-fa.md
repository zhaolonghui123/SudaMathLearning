# 分离变量法

$$
def \quad \frac{\text{d}y}{\text{d}x} = g(x)h(y)
$$

$$
解：1) y = y_0 \quad s.t. \quad h(y) = 0 则 y = y_0 是方程的解 \\ 2) h(y) \neq 0 \\ \frac{\text{d}y}{h(y)} = g(x) \text{d}x \\ \int \frac{\text{d}y}{h(y)} = \int g(x) \text{d}x \\ H(y) = G(x) + C
$$

$$
例1、求\quad \frac{dy}{dx} = 2x(1-y^2)^{\frac{1}{2}}的解
$$

​

$$
解：1) \quad 显然，y= \pm 1 是方程的解 \\ 2)1-y^2 \neq 0 \quad \\分离变量 \qquad \frac{dy}{\sqrt{1-y^2}} = 2xdx \\ 两端积分得\quad \int \frac{dy}{\sqrt{1-y^2}} = \int 2xdx \\ arcsiny=x^2+c \\ y = sin(x^2+c) \\ 3)y = \begin{cases}
-1\\
sin(x^2+c) \qquad x^2+c \in (-\frac{\pi}{2},\frac{\pi}{2})\\
1\\
\end{cases}
$$

$$
例2 \quad 求\frac{dy}{dx}= \frac{2xy^2}{1-x^2}\quad y(0)=1的特解
$$

$$
解：\quad \frac{dy}{y^2}=\frac{2x}{1-x^2} \\ 两端积分 \quad \int \frac{dy}{y^2}=\int \frac{2x}{1-x^2}dx \\ - \int \frac{dy}{y^2} = \int \frac{1}{1-x^2}d(1-x^2) \\ \frac{1}{y} = ln|1-x^2|+c \\ y(0)=1得c=1 \\ 满足y(0)=1的特解为 \frac{1}{y} = ln|1-x^2|+1
$$



​
