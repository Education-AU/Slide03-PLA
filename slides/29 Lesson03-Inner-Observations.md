---
title: Observations of inner product
template: default
---



#### Linear independence
Any set of **orthogonal** vectors are linear independent. Because

$$
\begin{aligned}
\sum _{i=1}^n c_i\mathbf{u}_i&=\mathbf{0} \Rightarrow \\
\langle \mathbf{u}_k,\sum _{i=1}^n c_i\mathbf{u}_i\rangle&=
c_k\langle \mathbf{u}_k,\mathbf{u}_k\rangle=0
\end{aligned}
$$

which implies $c_k=0$ for all $k$

#### Pythagoras theorem

If $\mathbf{u}$ and $\mathbf{v}$ are orthogonal then

$$
\lVert \mathbf{u}+\mathbf{v}\rVert^2= \lVert \mathbf{u}\rVert^2 +\lVert \mathbf{v}\rVert^2
$$

If $\mathbf{u}$ and $\mathbf{v}$ are orthogonal vectors that is $\langle \mathbf{u},\mathbf{v} \rangle=0$ then

$$
\lVert \mathbf{u}+\mathbf{v}\rVert^2=
\langle \mathbf{u}+\mathbf{v},\mathbf{u}+\mathbf{v} \rangle=
\lVert \mathbf{u}\rVert^2 +\lVert \mathbf{v}\rVert^2 +2\langle \mathbf{u},\mathbf{v} \rangle
=\lVert \mathbf{u}\rVert^2 +\lVert \mathbf{v}\rVert^2
$$

