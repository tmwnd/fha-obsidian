---
title: Pseudoinverse
type: definition
---

Sei $X \in \mathbb{R}^{m \times n}$.

Zerlege $X$ über [[Singulärwertzerlegung|SVD]] in $U\Sigma V^T$ mit
- $r \le \min(m, n)$
- $\Sigma^+ = \text{diag}(\frac{1}{\sigma_1}, \dots, \frac{1}{\sigma_r}, 0, \dots, 0)$^[Falls $\sigma_1 \gg \sigma_{k+1}$ mit $k \le r$ verstärkt dieser Schritt die Messfehler von $X$]

Die *Pseudoinverse* $X^+$ von $X$ ist definiert als
- $X^+ = V\Sigma^+U^T$