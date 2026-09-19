---
title: General Orthogonal Projection
template: default
---

Can we make a similar statement? Consider any $\mathbf{u} \in V$.

Can we find the closets point to $\mathbf{u} \in W$

To do this we choose an **orthogonal** basis in $W$
$$
\mathbf{e}_1,\mathbf{e}_2,\dots,\mathbf{e}_k
$$
And we simply make the same operation on each basis vector as we did in the simple case and sum up
$$
\mathbf{u}_{\parallel}=\sum_{i=1}^k \frac{\langle \mathbf{u},\mathbf{e}_i \rangle}{\langle \mathbf{e}_i,\mathbf{e}_i \rangle }\mathbf{e}_i
$$
This is our candidate projection. So we construct the vector orthogonal to $W$
$$
\mathbf{u}_{\perp}=\mathbf{u}-\mathbf{u}_{\parallel}=\mathbf{u}-\sum_{i=1}^k \frac{\langle \mathbf{u},\mathbf{e}_i \rangle}{\langle \mathbf{e}_i,\mathbf{e}_i \rangle }\mathbf{e}_i
$$  

