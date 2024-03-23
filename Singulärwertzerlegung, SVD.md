Sei $A \in \mathbb{R}^{m \times n}$.

Zerlege $A$, sodass
- $A = U\Sigma V^T$
- $U \in \mathbb{R}^{m \times m}$
- $r \le \min(m, n)$
- $\sigma_1 \ge \dots \ge \sigma_r \gt 0$ die [[Singulärwerte]] von $A$
- $\Sigma = \text{diag}(\sigma_1, \dots, \sigma_r, 0 \dots, 0) \in \mathbb{R}^{m \times n}$
- $V = \text{span}(v_1, \dots, v_n) \in \mathbb{R}^{n \times n}$
- $U, V$ [[orthonormal]]

mit
- $f(v) = \| Av \|_2^2$
- $f(v_k) = \sigma_1^2$
- $v_1 = \arg\max_{\| v \|_2^2 = 1} f(v) = \arg\min_{\| v \|_2^2 \le 1} f(v)$
- $V_k = \text{span}(v_1, \dots, v_k) \in \mathbb{R}^{n \times k}$
- $v_k = \arg\max_{\| v \|_2^2 = 1, v \perp V_{k-1}} f(v)$