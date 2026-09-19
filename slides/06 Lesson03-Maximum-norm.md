---
title: Maximum norm validation
template: default
---


We have to prove the axioms of a norm

<h3 class="h3-blue">Proof:</h3>

1. **Positive definite**:<br>
$\lVert \mathbf{f} \rVert\in \mathbb{R}$ by definition and also $\lVert \mathbf{f} \rVert \geq 0$
2. **Positive definite**:<br>
If $\lVert \mathbf{f} \rVert=0$ then all $f(x)$ must be $0$ for all $x$, and therefore $\mathbf{f}=\mathbf{0}$    
3. **Absolute Scalability**:<br>
$\lVert s\mathbf{f} \rVert = \max_{x \in [a,b]} \lvert sf(x)\rvert = \max_{x \in [a,b]} \lvert s\rvert \lvert f(x)\rvert =\lvert s\rvert \max_{x \in [a,b]} \lvert f(x)\rvert=\lvert s\rvert\lVert \mathbf{f} \rVert$
4. **Triangle Inequality**:<br>
Follows from the triangle inequality for real numbers<br>
$\lvert f+g \rvert \leq \lvert f \rvert + \lvert g\rvert$
