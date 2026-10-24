---
title: Exercise 3 Solution
template: two-column
---


#### Solution a

``` python runnable Solution a
import numpy as np
x=np.array([1, 2, 3, 4])
y=np.array([1, 1, 1, 1])
print(x)
print(y)
product=np.sum(x*y)
L2_x=np.sqrt(np.sum(x**2))
L2_y=np.sqrt(np.sum(y**2))
print(product)
print(L2_x)
print(L2_y)

```

<!-- column -->

#### Solution b

``` python runnable Solution b
import numpy as np
b_1=np.array([1, 1,-1,1])
b_2=np.array([1, 1,0,1])
b_3=np.array([1, -1, 1,1])
b_4=np.array([1, 0, 1,0])
B= np.column_stack((b_1,b_2,b_3,b_4))
print(B)
print(np.linalg.det(B))

x=B@np.array([1, 2, 3, 4])
y=B@np.array([1, 1, 1, 1])
print(x)
print(y)

product=np.sum(x*y)
product_2= np.array([1, 2, 3, 4])@B.T@B@np.array([1, 1, 1, 1])
L2_x=np.sqrt(np.sum(x**2))
L2_y=np.sqrt(np.sum(y**2))
print(product)
print(product_2)
print(L2_x)
print(L2_y)
```

The formula for the inner product becomes in matrix formulation for the standard basis is $x^Ty$

So when the new coordinates are $x'=Bx$ and $y'=By$ the inner product becomes $(Bx)^T (By)=x^TB^TBy.

