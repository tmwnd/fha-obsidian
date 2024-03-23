Sei $X \in \mathbb{R}^{m \times n}$ mit
- $U\Sigma V^T$ der [[Singulärwertzerlegung, SVD|SVD]] von $X$
- $\sigma_r \gt \sigma_{r+1} = 0$
- $U_r = (u_1, \dots, u_r) \in \mathbb{R}^{m \times r}$
- $\Sigma_r = \text{diag}(\sigma_1, \dots, \sigma_r) \in \mathbb{R}^{r \times r}$
- $V_r = (u_1, \dots, u_r) \in \mathbb{R}^{n \times r}$

Es gilt
- $X = U\Sigma V^T = \sum_{i=1}^r u_i\sigma_iv_i^T = U_r\Sigma_rV_r^T$
- $X^+ = V_r\Sigma_r^{-1}U_r^T$ die [[Pseudoinverse]] von $X$

Falls $r \ll \min(m, n)$ gilt
- Produkte über $U_r\Sigma_rV_r^T$ deutlich günstiger als über $X$
- Produkte über $V_r\Sigma_r^{-1}U_r^T$ deutlich günstiger als über $X^+$

Falls $\sigma_1 \gg \sigma_{k+1}$, $k \ll r$ gilt

$$
	X = U\Sigma V^T = \sum_{i=1}^r u_i\sigma_iv_i^T \approx \sum_{i=1}^k u_i\sigma_iv_i^T = U_k\Sigma_kV_k^T = X_k
$$

und
- Produkte über $X_k$ deutlich günstiger als über $X$