Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $X$ ein $p$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]] auf $(\Omega, \mathcal{A}, P)$, $Y$ ein $q$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]] auf $(\Omega, \mathcal{A}, P)$.

$X$ und $Y$ sind [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]], falls

$$
	\forall (w, z) \in \mathbb{R}^p \times \mathbb{R}^q : \text{E}[e^{iw^T+iz^TY}] = \text{E}[e^{iw^TX}] \cdot \text{E}[e^{iz^TY}]
$$

---

Sei $1 \le p \lt d$, $Z \sim \mathcal{N}(\mu, \Sigma)$ ein $d$-dimensionaler [[zettel/Normalverteilung|normalverteilter]] [[zettel/Zufallsvariable|Zufallsvektor]] mit der [[zettel/Kovarianz|Kovarianzmatrix]] Cov und
- $X = (Z_1, \dots, Z_p)$
- $Y = (Z_{p+1}, \dots, Z_d)$
- $\Sigma_X = \text{Cov}[X]$
- $\Sigma_Y = \text{Cov}[Y]$

$X$ und $Y$ sind [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]], falls

$$
	\Sigma = \begin{pmatrix} \Sigma_X & 0 \\ 0 & \Sigma_Y \end{pmatrix}
$$