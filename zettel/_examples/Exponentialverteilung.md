Sei $\lambda \in (0, \infty)$, $t \gt 0$ und die $\lambda$-[[zettel/λ-Dichte|Dichte]] $e_\lambda$ definiert als

$$
	e_\lambda(t) := \lambda e^{-\lambda t}
$$

Sei $x \in \mathbb{R}$.

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] einer reelwertigen [[zettel/Zufallsvariable|Zufallsvariable]] $X$ heißt *exponentialverteilt*, falls

$$
	F(x) = \begin{cases}
		0 & x \ge 0 \\
		\int_0^x e_\lambda(t) dt & x \gt 0
	\end{cases}
$$

Schreibe
- $X \sim \text{Exp}(\lambda)$

---

Sei $X \sim \text{Exp}(\lambda)$ eine [[zettel/Zufallsvariable|Zufallsvariable]].

Es gilt
- $\text{E}[X] = \frac{1}{\lambda}$
- $\text{Var}[X] = \frac{1}{\lambda^2}$