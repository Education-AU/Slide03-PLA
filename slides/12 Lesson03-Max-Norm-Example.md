---
title: Max norm example
template: default
---

Consider the space $C[-\infty,\infty ]$ of continuous functions on the real axis.

And consider the specific functions, where $\alpha \in \mathbb{R}$
$$
\begin{aligned}
f_1(t)&=\cos(t)\\
f_2(t)&=\cos(t+\alpha)
\end{aligned}
$$

We want to calculate the distance between these functions using the max-norm.
$$
\lvert \cos(t+\alpha)-\cos(t) \rvert =\lvert 2\sin (\frac{\alpha}{2}) \sin(t+\frac{\alpha}{2})\rvert
$$
And since $\sin(t+\frac{\alpha}{2})$ has $max =1$, the max value becomes

$$\lvert 2\sin (\frac{\alpha}{2})\rvert$$

That is, the distance between the two functions is
$$
d(f_1,f_2)=\lvert 2\sin (\frac{\alpha}{2})\rvert
$$

