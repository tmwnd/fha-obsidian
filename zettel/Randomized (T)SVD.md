Sei $X \in \mathbb{R}^{m \times n}$, $k+p \ll n$, $\Omega \in \mathbb{R}^{m \times (k+p)}$ mit
- $\forall i \in \{ 1, \dots, m \}, j \in \{ 1, \dots, n \} : \omega_{ij} \sim \mathcal{N}(0, 1)$
- $\tilde{X} = X\Omega \in \mathbb{R}^{m \times (k+1)}$
- $U\Sigma V^T$ die [[zettel/Singulärwertzerlegung|SVD]] von $\tilde{X}$

---

Vorteile:
- $U\Sigma V^T$ ist eine Näherung für die [[zettel/Singulärwertzerlegung|SVD]] von $X$
- $U\Sigma V^T$ deutlich günstiger zu berechnen als die [[zettel/Singulärwertzerlegung|SVD]] von $X$