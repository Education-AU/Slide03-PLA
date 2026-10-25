---
title: Exercise 4 Inner product
template: two-column
show-footer: false
---

#### Exercise a

The inner product defines angles

Consider coordinates  $x= (1,2,3)$ and $y= (1,1,1)$ for two vectors in $\mathbb{R}^3$. Where coordinates are in the
standard basis

Calculate angle between the vectors

#### Solve in python

``` python runnable Exercise a
import numpy as np
x=np.array([[1, 2, 3]]).T
y=np.array([[1, 1, 1]]).T
print(x)
print(y)
angle=0//correct
print(angle)
```

<!-- column -->

#### Exercise b

Do the same but now consider the coordinates of the vectors in a different basis. The new basis is defined by the
following vectors:

$\mathbf{b}_1 = (1, 1, -1), \mathbf{b}_2 = (1, 1, 0), \mathbf{b}_3 = (1, -1, 1)$

#### Solve in Python

``` python runnable Exercise b
import numpy as np
b_1=np.array([1, 1,-1])
b_2=np.array([1, 1,0])
b_3=np.array([1, -1, 1])

B=np.column_stack((b_1, b_2, b_3))
print(B)
print(np.linalg.det(B))

x=np.array([[1, 2, 3]]).T
y=np.array([[1, 1, 1]]).T
print(x)
print(y)
angle=0#correct
print(angle)
```