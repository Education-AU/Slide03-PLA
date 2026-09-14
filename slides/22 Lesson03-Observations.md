---
title: Important Observations
template: default
---


First, the norm of a vector space is defined on the vectors themselves, not on their coordinates in an arbitrary basis.
To compute the norm, one must work with the actual vectors (or translate coordinates back to the original vectors)
rather than blindly applying the formula to the coordinates in a different basis.

But inner product norms have a very specific type of coordinate invariance that we discover later


For example in $\mathbb{R}^2$ the vector $\mathbf{v}= (10,-3)$ has $L_1$-norm

$$
\lVert \mathbf{v} \rVert_1=\lvert 10 \rvert+\lvert -3 \rvert=13
$$
But if the vector is represented in say the basis $\mathbf{b}_1= (1,1),\mathbf{b}_2= (-1,1)$
$$
\mathbf{v}=\frac{7}{2}\mathbf{b}_1+ \frac{-13}{2}\mathbf{b}_2
$$
And the calculating the norm by using the coordinates it will produce the wrong result
$$
\lvert \frac{7}{2}\rvert+\lvert \frac{-13}{2}\rvert=\frac{20}{2}=10
$$
This shows that, in general, norms must be calculated on the vectors themselves, or by a rule that is correctly adapted
to the specific basis.


