---
title: Exercise 2 Metrics
template: two-column
---

You can solve the problem directly in the browser extending the following code:

#### Exercise a

Consider coordinates  $x= (1,2,3,4)$ and $y= (1,1,1,1)$ for two vectors in $\mathbb{R}^4$. Where coordinates are in the
standard basis

Calculate the distances between the vectors induced by the three standard norms:

#### Solve in python

``` python runnable Exercise a
import numpy as np
x=np.array([1, 2, 3, 4])
y=np.array([1, 1, 1, 1])
print(x)
print(y)
D1_x=0//correct
D2_x=0//correct
Dmax_x=0//correct
print(D1_x)
print(D2_x)
print(Dmax_x)

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
D1_x=np.sum(np.abs(x-y))// correct
D2_x=np.sqrt(np.sum((x-y)**2))// correct
Dmax_x=np.max(np.abs(x-y))// correct
print(D1_x)
print(D2_x)
print(Dmax_x)
```
