---
title: Orthonormal basis properties
template: default
---

Orthonormal bases have very nice properties and are therefore used extensively. Let us consider the inner product of vectors in such a basis.

So consider a finite dimensional **real** vector space $V$ equipped with an inner product.t.

Let $\mathbf{u},\mathbf{v}\in V$ and let $\mathbf{b}_i$ be a **orthonormal** basis of $V$.

Then we can expand $\mathbf{u},\mathbf{v}$ in the basis
$$
\mathbf{u}=\sum_{i=1}^n c_i\mathbf{b}_i \quad \mathbf{v}=\sum_{j=1}^n d_j\mathbf{b}_j
$$


And calculate the inner product
$$
\langle \mathbf{u},\mathbf{v} \rangle=
\langle \sum_{i=1}^n c_i\mathbf{b}_i,\sum_{j=1}^n d_j\mathbf{b}_j \rangle=
\sum_{i=1}^n\sum_{j=1}^n c_id_j \langle \mathbf{b}_i,\mathbf{b}_j \rangle
=\sum_{i=1}^n c_id_i
$$
since the basis is orthonormal.

And so we observe that the inner product is calculated the same way in any **orthonormal basis** and on the **coordinates** in that basis.

And the way it is calculated is in fact our definition of inner product on $\mathbb{R}^n$



