---
title: Exercise 1 Solution
template: two-column
---

#### Solution a.

``` python runnable Solution a
import numpy as np
x=np.array([1, 2,3])
L1_x=np.sum(np.abs(x))
L2_x=np.sqrt(np.sum(x**2))
Lmax_x=np.max(x)
print(L1_x)
print(L2_x)
print(Lmax_x)
```

<!-- column -->

#### Solution b.

``` python runnable Solution b
import numpy as np
b_1=np.array([1, 1,-1])
b_2=np.array([1, 1,0])
b_3=np.array([1, -1, 1])

B=np.column_stack([b_1, b_2, b_3])
print(B)
print(np.linalg.det(B))

x=B@np.array([1, 2,-3])
print(x)
L1_x=np.sum(np.abs(x))
L2_x=np.sqrt(np.sum(x**2))
Lmax_x=np.max(x)
print(L1_x)
print(L2_x)
print(Lmax_x)
```
