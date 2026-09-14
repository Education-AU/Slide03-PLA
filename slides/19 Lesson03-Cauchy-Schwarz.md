---
title: The Cauchy-Schwarz inequality
template: default
---

To actually convince ourselves that $\sqrt{\langle v,v \rangle}$ is a norm we need a **general** property of the
inner product, namely

$$
\lvert \langle \mathbf{u},\mathbf{v} \rangle \rvert \leq \lVert \mathbf{u} \rVert \lVert \mathbf{v} \rVert
$$

We look at this in the real vector space context but the complex case goes the same way.

First off, if $\mathbf{v}=\mathbf{0}$ then the inequality holds.

Now assume  $\mathbf{v}\neq \mathbf{0}$ and consider
$$
\langle (\mathbf{u}-\alpha \mathbf{v}), (\mathbf{u}-\alpha \mathbf{v}) \rangle\geq 0 \text{ where } \alpha=\frac{\langle \mathbf{u},\mathbf{v} \rangle}{\langle \mathbf{v},\mathbf{v}\rangle}
$$


Using the linearity and positive definiteness property of the inner product we obtain
$$
\langle \mathbf{u},\mathbf{u} \rangle +\alpha ^2 \langle \mathbf{v},\mathbf{v} \rangle-2\alpha \langle
\mathbf{u},\mathbf{v} \rangle \geq 0
$$