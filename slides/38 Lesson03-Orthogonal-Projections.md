---
title: Orthogonal Projections
template: default
---

Can we represent the vector $\mathbf{u}$ in this new set of vectors
.
Well clearly
$$
\mathbf{u}_{\parallel}+\mathbf{u}_{\perp}=
\frac{\langle \mathbf{u},\mathbf{v}\rangle}{\langle \mathbf{v},\mathbf{v}\rangle}\mathbf{v}+
\mathbf{u}-\frac{\langle \mathbf{u},\mathbf{v}\rangle}{\langle \mathbf{v},\mathbf{v}\rangle}\mathbf{v}=\mathbf{u}
$$
so yes we can. And since $\mathbf{u}_{\parallel}$ and $\mathbf{u}_{\perp}$ are orthogonal it is a basis.

From the previous discussion we saw that we can **project** the vector $\mathbf{u}$ down to vector $\mathbf{v}$ such
that the parallel vector $\mathbf{u}_{\parallel}$ is the vector parallel to $\mathbf{v}$ closest to $\mathbf{u}$
By the formula
$$
\mathbf{u}_{\parallel}=\frac{\langle \mathbf{u},\mathbf{v} \rangle}{\langle \mathbf{v},\mathbf{v} \rangle}\mathbf{v}
$$
And such that
$$
\mathbf{u}_{\perp}=\mathbf{u}-\mathbf{u}_{\parallel}
$$
is orthogonal to $\mathbf{u}_{\parallel}$. And such that
$$
\mathbf{u}=\mathbf{u}_{\perp}+\mathbf{u}_{\parallel}
$$
This construction of $\mathbf{u}_{\parallel}$ is called the orthogonal projection of $\mathbf{u}$ onto $\mathbf{v}$
