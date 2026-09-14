---
title: Justification of the angle concept in ℝ²
template: default
---


The two vectors can be represented on polar coordinates as

$$
\begin{aligned}
\mathbf{v}_1= r_1(\cos(\theta),\sin(\theta))\\
\mathbf{v}_2= r_2(\cos(\phi),\sin(\phi))
\end{aligned}
$$

where $r_1,r_2$ are the lengths of the vectors

Let's calculate the inner product we defined on $\mathbb{R}^2$

$$
\langle \mathbf{v}_1,\mathbf{v}_2 \rangle=r_1r_2\cos(\theta)\cos(\phi)+r_1r_2\sin(\theta)\sin(\phi)
$$
Using the cosine relation
$$
\cos(x-y)=\cos(x)\cos(y)+\sin(x)\sin(y)
$$
we get
$$
\langle \mathbf{v}_1,\mathbf{v}_2 \rangle=r_1r_2\cos(\theta-\phi)
$$

