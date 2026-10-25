---
title: Exercise 3 Inner product
template: two-column
show-footer: false
---

#### Exercise a

Consider coordinates  $x= (1,2,3,4)$ and $y= (1,1,1,1)$ for two vectors in $\mathbb{R}^4$. Where coordinates are in the
standard basis

1. Calculate the inner product of the vectors
2. Also calculate the $L_2$ norm for both vectors **using the inner product**

#### Solve in python

``` python runnable Exercise a
import numpy as np
x=np.array([1, 2, 3, 4])
y=np.array([1, 1, 1, 1])
print(x)
print(y)
product=0# correct
L2_x=0# correct
L2_y=0# correct

print(product)
print(L2_x)
print(L2_y)
```

<!-- column -->

#### Exercise b

Do the same but now consider the coordinates of the vectors in a different basis. The new basis is defined by the
following vectors:

$\mathbf{b}_1 = (1, 1, -1,1), \mathbf{b}_2 = (1, 1, 0,1), \mathbf{b}_3 = (1, -1, 1,1), \mathbf{b}_4 = (1, 0, 1,0)$

#### Solve in Python

``` python runnable Exercise b
import numpy as np
b_1=np.array([1, 1,-1,1])
b_2=np.array([1, 1,0,1])
b_3=np.array([1, -1, 1,1])
b_4=np.array([1, 0, 1,0])
B=([[0,0,0,0],[0,0,0,0],[0,0,0,0],[0,0,0,0]]) //correct
print(B)
print(np.linalg.det(B))
x=np.array([1, 2, 3, 4])// correct
y=np.array([1, 1, 1, 1])// correct
print(x)
print(y)
product=np.sum(x*y)
L2_x=np.sqrt(np.sum(x**2))
L2_y=np.sqrt(np.sum(y**2))
print(product)
print(L2_x)
print(L2_y)
```
Try to think about the formula for calculating the inner product in a different basis. You can use the matrix $B$ to
transform the coordinates of the vectors to the new basis and then calculate the inner product and norms in that basis
using matrix notation.