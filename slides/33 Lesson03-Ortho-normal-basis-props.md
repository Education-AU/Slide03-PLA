---
title: Matrix multiplication as inner product
template: default
---

Since orthonormal basis have this nice property we can exploit that for calculational purposes.

The inner product in any **orthonormal basis** can be expressed in coordinates in matrix language as
$$
\mathbf{c}^T \mathbf{d} =
\begin{bmatrix}
c_1 & c_2 & \cdots & c_n
\end{bmatrix}
\begin{bmatrix}
d_1 \\
d_2 \\
\vdots \\
d_n
\end{bmatrix}
$$
where now the $\mathbf{c}$ and $\mathbf{d}$ symbols are coordinate "vectors" and the convention is that all coordinate vectors are vertical.

In numpy these conventions are used to calculate inner products in coordinates.

