---
title: Exercise 4 Solution
template: two-column
---

#### Exercise a

``` python runnable Solution a
import numpy as np
x=np.array([[1, 2, 3]]).T
y=np.array([[1, 1, 1]]).T
print(x)
print(y)
angle=np.arccos(x.T@y/np.sqrt(x.T@x*y.T@y))
print(angle)
```

<!-- column -->

#### Exercise b

``` python runnable Solution b
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
angle=np.arccos(x.T@.T@B@y/np.sqrt(x.T@B.T@B@x*y.T@B.T@B@y))
print(angle)
```