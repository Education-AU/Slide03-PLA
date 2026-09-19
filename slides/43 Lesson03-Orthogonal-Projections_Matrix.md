---
title: Orthogonal Projection in matrix formulation
template: default
---

The procedure for finding the orthogonal projection as stated previously can be elegantly formulated in the language of
matrices.

Since $W$ is a subspace we can choose any basis of $W$. But with the lower dimension $k$

$$
\mathbf{b}_1,\mathbf{b}_2,\dots ,\mathbf{b}_k
$$

To simplify things we choose to express the vectors $\mathbf{b}_i$ in the standard basis organized in a matrix $A$ with
shape $n\times k$

$$
A=
\begin{bmatrix}
b_{11} & b_{12} & \cdots & b_{1k}\\
b_{21} & b_{22} & \cdots & b_{2k}\\
\vdots & \vdots & \cdots & b_{2k}\\
b_{n1} & b_{n2} & \cdots & b_{nk}
\end{bmatrix}
$$
$b_{1i},b_{2i},\dots b_{ni}$ being the coordinates of the $\mathbf{b}_i$ basis vector in standard coordinates.  

