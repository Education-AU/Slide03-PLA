---
title: Verification of Inner product on ℝⁿ
template: default
---

Does this inner product fulfill the requirements


1. **Symmetry**<br>
The symmetry is obvious by the symmetry of multiplication in $\mathbb{R}$
2. **Linearity**<br>
$\langle \mathbf{u}+\mathbf{v},\mathbf{w} \rangle=\sum_{i=1}^{n}(u_i+v_i)w_i=\sum_{i=1}^{n}(u_iw_i+v_iw_i)=\sum_{i=1}^{n}u_iw_i+ \sum_{i=1}^{n}v_iw_i= \langle \mathbf{u},\mathbf{w}\rangle +\langle \mathbf{v},\mathbf{w} \rangle$<br>
$\langle s\mathbf{u},\mathbf{v} \rangle=\sum_{i=1}^{n}su_iv_i=s\sum_{i=1}^{n}u_iv_i =s\langle \mathbf{u},\mathbf{v} \rangle$<br>
3. **Positive definiteness**<br>
Obviously $\langle \mathbf{u},\mathbf{u} \rangle \geq 0$ and <br>
$\langle \mathbf{u},\mathbf{u} \rangle =0 \Rightarrow\sum_{i=1}^{n}u_iu_i=0$<br>
And since all terms in the sum are non-negative all must be zero, so for all $i$ $u_i=0$
