---
title: Exercise 2 Solution
template: two-column
---

#### Solution a.

``` python runnable Solution a
import numpy as np
x=np.array([1, 2, 3, 4])
y=np.array([1, 1, 1, 1])
D1_x=np.sum(np.abs(x-y))
D2_x=np.sqrt(np.sum((x-y)**2))
Dmax_x=np.max(np.abs(x-y))
print(D1_x)
print(D2_x)
print(Dmax_x)
```

<!-- column -->

#### Solution b.

``` python runnable Exercise b
import numpy as np
b_1=np.array([1, 1,-1,1])
b_2=np.array([1, 1,0,1])
b_3=np.array([1, -1, 1,1])
b_4=np.array([1, 0, 1,0])

B=np.column_stack([b_1, b_2, b_3, b_4])
print(B)
print(np.linalg.det(B))

x=B@np.array([1, 2, 3, 4])
y=B@np.array([1, 1, 1, 1])

print(x)
print(y)
D1_x=np.sum(np.abs(x-y))
D2_x=np.sqrt(np.sum((x-y)**2))
Dmax_x=np.max(np.abs(x-y))
print(D1_x)
print(D2_x)
print(Dmax_x)
```