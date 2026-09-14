---
title: Metric space in normed vector Space
template: default
---

We now have a measure of length. But what about distance?

Having a norm at our disposal we can define a metric(*distance*), but first we need a definition

In general a metric $d$ on a vector space $V$( or any set really) is defined as

<h3 class="h3-blue">Definition</h3>

1. The metric map<br>
$d:V\times V\rightarrow \mathbb{R}$
2. Positive definite<br>
$\forall \mathbf{u},\mathbf{v} \in V: d(\mathbf{u},\mathbf{v})\geq 0, d(\mathbf{u},\mathbf{v})=0 \Rightarrow \mathbf{u}=\mathbf{v}$
3. Symmetry<br>
$\forall \mathbf{u},\mathbf{v} \in V: d(\mathbf{u},\mathbf{v})=d(\mathbf{v},\mathbf{u})$
4. Triangle inequality<br>
$\forall \mathbf{u},\mathbf{v},\mathbf{w} \in V: d(\mathbf{u},\mathbf{w})\leq d(\mathbf{u},\mathbf{v})+d(\mathbf{v},\mathbf{w})$
