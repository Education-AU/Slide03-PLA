---
title: Norms on ℝⁿ
template: default
---

Again we turn to our favorite vector space. We can define many norms on any given vector space. This is also the case on $\mathbb{R}^n$. 

The most used norms are
<h3 class="h3-blue">Maximum norm</h3>

Let $\mathbf{v}=(x_1,x_2,\dots ,x_n)\in \mathbb{R}^n$ then maximum norm denoted $\lVert \mathbf{v} \rVert_{\infty}$ is defined by
$\lVert v \rVert_{\infty} =\max_{i \in [0..n]}\lvert x_i \rvert$

<h3 class="h3-blue">$L_1$ norm</h3>

Let $\mathbf{v}=(x_1,x_2,\dots ,x_n)\in \mathbb{R}^n$ then $L_1$ norm denoted $\lVert \mathbf{v} \rVert_{1}$ is defined by
$\lVert v \rVert_{1} =\sum_{i=1}^n \lvert x_i \rvert$

<h3 class="h3-blue">$L_2$ norm</h3>
Let $\mathbf{v}=(x_1,x_2,\dots ,x_n)\in \mathbb{R}^n$ then $L_2$ norm denoted $\lVert \mathbf{v} \rVert_{2}$ is defined by
$\lVert \mathbf{v} \rVert_{2} =\sqrt{\sum_{i=1}^n \lvert x_i \rvert^{2}}$

It can be shown that all these norms satisfy the three properties of a norm.

The $L_2$ norm will be the most used norm in this course. 
It is also called the Euclidean norm since it is the norm that corresponds to 
the Euclidean distance between two points in $\mathbb{R}^n$. And it is induced by the usual
inner product on $\mathbb{R}^n$ which we'll come back to.