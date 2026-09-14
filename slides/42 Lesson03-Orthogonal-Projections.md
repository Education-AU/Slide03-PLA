---
title: General Orthogonal Projection
template: default
---

We have to prove that this candidate is orthogonal to all the vectors in $W$ which is the case if it is orthogonal to
all basis vectors in $W$.
$$
\langle \mathbf{u}-\sum_{i=1}^k \frac{\langle \mathbf{u},\mathbf{e}_i \rangle}{\langle \mathbf{e}_i,\mathbf{e}_i \rangle }\mathbf{e}_i,\mathbf{e}_j \rangle=
\langle \mathbf{u},\mathbf{e}_j\rangle-\frac{\langle \mathbf{u},\mathbf{e}_j \rangle}{\langle \mathbf{e}_j,\mathbf{e}_j \rangle }\langle \mathbf{e}_j,\mathbf{e}_j\rangle=0
$$

Is it the minimal distance solution? Consider any $\mathbf{w} \in W$
$$
\lVert \mathbf{u}-\mathbf{w} \rVert^2=
\lVert \mathbf{u}-\mathbf{w}_{\parallel}+\mathbf{w}_{\parallel}-\mathbf{w} \rVert^2=\lVert \mathbf{u}-\mathbf{w}_{\parallel}\rVert^2+\lVert\mathbf{w}_{\parallel}-\mathbf{w} \rVert^2
$$
since $\mathbf{w}_{\parallel}-\mathbf{w} \in W$

And this is uniquely minimal if $\mathbf{w}=\mathbf{w}_{\parallel}$

and furthermore
any $\mathbf{u} \in V$ can be expressed as a sum of the orthogonal projection $\mathbf{w}_{\parallel} $ and a vector
orthogonal to this projection
$$
\mathbf{u} = (\mathbf{u}-\mathbf{w}_{\parallel})+\mathbf{w}_{\parallel}  
$$
