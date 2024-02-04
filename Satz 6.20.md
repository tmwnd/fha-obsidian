Sei $(\Omega, \mathcal{A}, P)$ ein [[Maßraum|Wahrscheinlichkeitsraum]], $X$ ein $p$-dimensionaler [[Zufallsvariable|Zufallsvektor]] auf $(\Omega, \mathcal{A}, P)$, $Y$ ein $q$-dimensionaler [[Zufallsvariable|Zufallsvektor]] auf $(\Omega, \mathcal{A}, P)$.

$X$ und $Y$ sind [[Unabhängige Zufallsvariablen|unabhängig]], falls mit dem [[Erwartungswert]] $E$ gilt

$$
	\forall (w, z) \in \mathbb{R}^p \times \mathbb{R}^q : E[e^{iw^T+iz^TY}] = E[e^{iw^TX}] \cdot E[e^{iz^TY}]
$$

---

Sei $1 \le p \lt d$, $Z \sim \mathcal{N}(\mu, \Sigma)$ ein $d$-dimensionaler [[Normalverteilung|normalverteilter]] [[Zufallsvariable|Zufallsvektor]] mit der [[Covarianz|Kovarianzmatrix]] Cov und
- $X = (Z_1, \dots, Z_p)$
- $Y = (Z_{p+1}, \dots, Z_d)$
- $\Sigma_X = \text{Cov}(X)$
- $\Sigma_Y = \text{Cov}(Y)$

$X$ und $Y$ sind [[Unabhängige Zufallsvariablen|unabhängig]], falls

$$
	\Sigma = \begin{pmatrix} \Sigma_X & 0 \\ 0 & \Sigma_Y \end{pmatrix}
$$