---
title: Orthogonal Projections
template: default
---

We are not done yet, we need the orthogonal vector to $\mathbf{v}$

This is constructed as the drawing suggests by defining our candidate as
$$
\mathbf{u}_{\perp}=\mathbf{u}-\frac{\langle \mathbf{u},\mathbf{v}\rangle}{\langle \mathbf{v},\mathbf{v}\rangle}\mathbf{v}
$$
Now is this vector $\mathbf{u}_{\perp}$ orthogonal to $\mathbf{v}$? We calculate
$$
\langle\mathbf{u}_{\perp},\mathbf{v}  \rangle=
\langle \mathbf{u}-\frac{\langle \mathbf{u},\mathbf{v}\rangle}{\langle \mathbf{v},\mathbf{v}\rangle}\mathbf{v},\mathbf{v}  \rangle
=\langle \mathbf{u},\mathbf{v}\rangle -\langle \mathbf{u},\mathbf{v}\rangle =0
$$
So yes it is!



