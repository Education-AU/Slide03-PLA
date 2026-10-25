---
title: Exercise 6 Orthogonal Projection
template: default
show-footer: false
---

Consider coordinates  $x= (1,2,3,4,5,6)$ of a vector in the standard basis of $\mathbb{R}^6$

We want to project the vector $x$ onto the subspace spanned by the following vectors:

$y_1= (1,4,2,-1,0,0), y_2= (0,1,0,2,0,1), y_3= (1,0,1,0,1,0)$ also expressed in standard basis of $\mathbb{R}^6$

Let $x_{\parallel}$ be the projection and $x_{\perp}$ the orthogonal component of $x$ with respect to the subspace
spanned by $y_1, y_2, y_3$

Then verify that $x_{\perp}$ is orthogonal to the subspace spanned by $y_1, y_2, y_3$

Use the projection formula to calculate the projection and the orthogonal component

#### Solve in python

``` python runnable Exercise a
import numpy as np
y_1=np.array([1, 4, 2, -1, 0, 0]).reshape(-1,1)# column vectors
y_2=np.array([0, 1, 0, 2, 0, 1]).reshape(-1,1)
y_3=np.array([1, 0, 1, 0,1, 0]).reshape(-1,1)
x=np.array([1, 2, 3, 4, 5, 6]).reshape(-1,1)

P=0#correct
print(P)

projection=0#correct 
ortogonal=0#correct

#verify orthogonality
print(y_1.T@ortogonal)
print(y_2.T@ortogonal)
print(y_3.T@ortogonal)

```

