---
title: Exercise 5 Solution
template: two-column
---

#### Solution a

``` python runnable Solution a
import numpy as np
x=np.array([[1, 1, 0]]).T
y=np.array([[1, -1, 0]]).T
z=np.array([[0, 0, 2]]).T

print(x.T@y)
print(x.T@z)
print(y.T@z)

```

<!-- column -->

#### Solution b

``` python runnable Solution b
import numpy as np
x=np.array([[1, 1, 0]]).T
y=np.array([[1, -1, 0]]).T
z=np.array([[0, 0, 2]]).T

x_norm=x/np.linalg.norm(x)
y_norm=y/np.linalg.norm(y)
z_norm=z/np.linalg.norm(z)

print(x_norm)
print(y_norm)
print(z_norm)
```