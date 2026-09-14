---
title: Matrices inner products and transpose
template: default
---
$$
\langle y,Ax \rangle=\langle A^Ty,x \rangle
$$
How can we see this. Well simply be using what it means

If $A$ has shape $n\times k$
$$
(Ax)_i=\sum_{j=1}^k a_{ij}x_j, i=1 \dots n
$$
implying
$$
\langle Ax,y \rangle=\sum_{i=1}^n\sum_{j=1}^k a_{ij}x_jy_i=\sum_{j=1}^k x_j \sum_{i=1}^n a_{ij}y_i=\sum_{j=1}^k x_j \sum_{i=1}^n a^T_{ji}y_i=\langle x,A^Ty \rangle
$$

This can also be expressed in pure matrix terms.

Remember that the inner product
$$
\langle x,y \rangle= x^Ty
$$
In matrix language
