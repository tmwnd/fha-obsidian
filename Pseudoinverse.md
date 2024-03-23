Sei $X \in \mathbb{R}^{m \times n}$.

Zerlege $X$ über [[Singulärwertzerlegung, SVD|SVD]] in $U\Sigma V^T$ mit
- $r \le \min(m, n)$
- $\Sigma^+ = \text{diag}(\frac{1}{\sigma_1}, \dots, \frac{1}{\sigma_r}, 0, \dots, 0)$

Die *Pseudoinverse* $X^+$ von $X$ ist definiert als
- $X^+ = V\Sigma^+U^T$