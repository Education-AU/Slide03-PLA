---
title: Matrices inner products and transpose
template: default
---

Now going back to our projection equation
$$
\langle Aw,Ax_0 \rangle=\langle Aw,u \rangle
$$
we can use our rule to obtain
$$
\langle w,A^TAx_0 \rangle=\langle w,A^Ty \rangle
$$
for all $w$ which implies
$$
A^TAx_0=A^Ty \Rightarrow x_0=(A^TA)^{-1}A^Ty
$$
This is called the normal equations associated with the multivariate least-squares problem.

They are as an example central in linear regression and arise naturally in statistical estimation when the noise is assumed to be normally distributed.
