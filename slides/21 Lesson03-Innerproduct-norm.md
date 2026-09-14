---
title: An inner product induces a norm
template: default
---

Let us just verify this

1. Positive definite<br>
This comes directly from the positive definiteness of the inner product
2. Absolute scaling
$\lVert s\mathbf{v} \rVert=\sqrt{\langle s\mathbf{v},s\mathbf{v} \rangle}=\sqrt{s^2\langle \mathbf{v},\mathbf{v} \rangle}=\lvert s \rvert \sqrt{\langle \mathbf{v},\mathbf{v} \rangle} =\lvert s \rvert \lVert \mathbf{v} \rVert$
3. Triangle inequality


$$
\lVert \mathbf{u}+\mathbf{v} \rVert^2=\langle \mathbf{u}+\mathbf{v},\mathbf{u}+\mathbf{v} \rangle=\lVert \mathbf{u}\rVert^2 +\lVert \mathbf{v}\rVert^2+2\langle \mathbf{u},\mathbf{v} \rangle
$$
Since of course $\langle \mathbf{u},\mathbf{v} \rangle$ can be negative this equation implies
$$
\lVert \mathbf{u}+\mathbf{v} \rVert^2 \leq \lVert \mathbf{u}\rVert^2 +\lVert \mathbf{v}\rVert^2+2\lvert \langle \mathbf{u},\mathbf{v} \rangle \rvert
$$
Using the *Cauchy-Schwarz inequality* we get
$$
\lVert \mathbf{u}+\mathbf{v} \rVert^2 \leq \lVert \mathbf{u}\rVert ^2 +\lVert \mathbf{v}\rVert ^2 + 2\lVert \mathbf{u} \rVert \lVert\mathbf{v} \rVert
$$
which implies
$$
\lVert \mathbf{u}+\mathbf{v} \rVert^2
\leq
(\lVert \mathbf{u}\rVert  +\lVert \mathbf{v}\rVert )^2
$$
implying
$$
\lVert \mathbf{u}+\mathbf{v} \rVert
\leq
\lVert \mathbf{u}\rVert  +\lVert \mathbf{v}\rVert
$$


