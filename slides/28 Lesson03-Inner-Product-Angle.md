---
title: Justification of the angle concept in ℝ²
template: default
---

So in the case of $\mathbb{R}^2$ we see that the **angle** between the vectors is directly calculated from the inner product.

Now this can be generalized to any inner product on any vector space, because of the *Cauchy-Schwarz* inequality stating that for any inner product
$$
\lvert \langle \mathbf{u},\mathbf{v} \rangle \rvert \leq \lVert \mathbf{u} \rVert \lVert \mathbf{v} \rVert
$$
which implies
$$
-1 \leq \frac{\langle \mathbf{u},\mathbf{v} \rangle }{\lVert \mathbf{u} \rVert \lVert \mathbf{v} \rVert} \leq 1
$$
Since this is the case we define the angle by
$$
\cos^{-1}(\frac{\langle \mathbf{u},\mathbf{v} \rangle }{\lVert \mathbf{u} \rVert \lVert \mathbf{v} \rVert}) =\theta
$$
Notice that the angle by this definition is constrained to $[0,\pi]$. That is a non-signed angle, but the angle **between** the vectors.

