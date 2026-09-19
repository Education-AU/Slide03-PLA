---
title: Orthogonal Projections
template: default
---

There are several ways to think about this, but let us think about it this way.

Find the vector parallel to $\mathbf{v}$ that is closest to $\mathbf{u}$. Call this closest vector $\mathbf{u}_{\parallel}$

So minimize
$$
\lVert t\mathbf{v}-\mathbf{u} \rVert^2
=\langle t\mathbf{v}-\mathbf{u},t\mathbf{v}-\mathbf{u} \rangle
=
t^2\langle \mathbf{v},\mathbf{v}\rangle+
\langle \mathbf{u},\mathbf{u}\rangle
-2t\langle \mathbf{u},\mathbf{v}\rangle
$$
Differentiating by $t$ and setting equal to zero we get
$$
t\langle \mathbf{v},\mathbf{v}\rangle=
\langle \mathbf{u},\mathbf{v}\rangle
$$
And inserting the $t$ back as a scaling of $\mathbf{v}$ we get the closest vector
$$
\mathbf{u}_{\parallel}=
\frac{\langle \mathbf{u},\mathbf{v}\rangle}{\langle \mathbf{v},\mathbf{v}\rangle}\mathbf{v}
$$

