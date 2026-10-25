---
title: Exercise 6 Solution
template: default
show-footer: false
---

``` python runnable Solution
import numpy as np
y_1=np.array([1, 4, 2, -1, 0, 0]).reshape(-1,1)# column vectors
y_2=np.array([0, 1, 0, 2, 0, 1]).reshape(-1,1)
y_3=np.array([1, 0, 1, 0,1, 0]).reshape(-1,1)
x=np.array([1, 2, 3, 4, 5, 6]).reshape(-1,1)

P=np.hstack((y_1, y_2, y_3))#projection matrix
print(P)

projection=P@np.linalg.inv(P.T@P)@P.T@x#projection formula 
ortogonal=x-projection

#verify orthogonality
print(y_1.T@ortogonal)
print(y_2.T@ortogonal)
print(y_3.T@ortogonal)

```