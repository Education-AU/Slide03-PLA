---
title: Exercise 1 Norms
template: two-column
showFooter: false
---

#### Exercise a

Compute the L1, L2, and max norms of a vector. The vector is defined as:

$\mathbf{x} \in \mathbb{R}^3$ with coordinates $x = (1 , 2 , -3)$ in the standard basis.

#### Solve in python

``` python runnable Exercise a
import numpy as np
x=np.array([1, 2,-3])
print(x)
L1_x=0#correct
L2_x=0#correct
Lmax_x=0#correct
print(L1_x)
print(L2_x)
print(Lmax_x)

```

<!-- column -->

#### Exercise b

Now we have the same coordinates but in a different basis. The new basis is defined by the following vectors:

$\mathbf{b}_1 = (1, 1, -1), \mathbf{b}_2 = (1, 1, 0), \mathbf{b}_3 = (1, -1, 1)$

So we have to transform the coordinates to coordinates in the standard basis before calculating norms.
Remember that the columns of the transformation matrix $B$ are the coordinates of the old basis in the target basis

Also ensure that the matrix is invertible, otherwise the suggested basis is not a basis.

#### Solve in python

``` python runnable Exercise b
import numpy as np
b_1=np.array([1, 1,-1])
b_2=np.array([1, 1,0])
b_3=np.array([1, -1, 1])
B=([[0,0,0],[0,0,0],[0,0,0]]) #correct
print(B)
print(np.linalg.det(B))
x=0# correct
print(x)
L1_x=0# correct
L2_x=0# correct
Lmax_x=0# correct
print(L1_x)
print(L2_x)
print(Lmax_x)
```
