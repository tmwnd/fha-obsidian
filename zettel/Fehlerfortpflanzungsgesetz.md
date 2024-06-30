Seien $(Z_n)_{n \in \mathbb{N}}$ $d$-Dimensionale [[zettel/Zufallsvariable|Zufallsvektoren]], $\mu \in \mathbb{R}^d$, $\Sigma \in \mathbb{R}^{d \times d}$ symmetrisch positiv semidefinit, $f : \mathbb{R}^d \to \mathbb{R}^k$ eine [[zettel/Funktion|Funktion]] mit
- $\sqrt{n}(Z_n - \mu) \overset{V}{\longrightarrow} \mathcal{N}_d(0, \Sigma)$.
- $f$ in $\mu$ differenzierbar
- $J_f(\mu)$ die [[Jacobi-Matrix]] von $f$ an der Stelle $\mu$

Es gilt

$$
	\sqrt{n}(f(Z_n)) - f(\mu)) \overset{V}{\longrightarrow} \mathcal{N}_k(0, J_f(\mu)\Sigma J_f(\mu)^T))
$$