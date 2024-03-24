Sei $X \in \mathbb{R}^{m \times n}$.

Zerlege $X$, sodass
- $X = U\Sigma V^T$
- $U \in \mathbb{R}^{m \times m}$
- $r \le \min(m, n)$
- $\sigma_1 \ge \dots \ge \sigma_r \gt 0$ die [[Singulärwerte]] von $A$
- $\Sigma = \text{diag}(\sigma_1, \dots, \sigma_r, 0 \dots, 0) \in \mathbb{R}^{m \times n}$
- $V = \text{span}(v_1, \dots, v_n) \in \mathbb{R}^{n \times n}$
- $U, V$ [[orthogonale Matrizen|orthogonal]], [[quadratische Matrix|quadratisch]]

Es gilt
- $X^TX = V\Sigma^T\Sigma V^T$
- $XX^T = U\Sigma\Sigma^TU^T$
- $\sigma_1^2 \ge \cdots \ge \sigma_r^2 \gt 0$, $\sigma_{r+1} = \dots = \sigma_n = 0$ die [[Eigenwert|Eigenwerte]] von $X^TX$ bzw. $XX^T$
- Die Spalten von $V$ sind die [[Eigenvektor|Eigenvektoren]] von $X^TX$
- Die Spalten von $U$ sind die [[Eigenvektor|Eigenvektoren]] von $XX^T$

Berechne die [[Eigenwert|Eigenwerte]] $\lambda_1 \ge \cdots \ge \lambda_r \ge 0$, $\lambda_{r+1} = \cdots = \lambda_n = 0$ bzw. die [[Eigenvektor|Eigenvektoren]] $(v_i)_{i \in \{ 1, \dots, n \}}$ von $X^TX$ mit
- $\forall i \in \{ 1, \dots, n \} : \sigma_i = \sqrt{\lambda_i}$
- $V = (v_1, \dots, v_n)$

Es gilt
- $\forall i \in \{ 1, \dots, r \} : u_i = \frac{1}{\sigma_i}Xv_i$
- $u_1, \dots, u_m$ die zu einer [[Orthonormalbasis]] ergänzten $u_1, \dots, u_r$
- $U = (u_1, \dots, u_m)$