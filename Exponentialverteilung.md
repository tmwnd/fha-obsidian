Sei $\mu \in (0, \infty)$, $t \gt 0$ und

$$
	e_\lambda(t) = \lambda e^{-\lambda t}
$$

Sei $x \in \mathbb{R}$.

Die [[Verteilungsfunktion]] einer reelwertigen [[Zufallsvariable]] $X$ heißt *exponentialverteilt*, falls

$$
	F(x) = \begin{cases}
		0, \quad\quad\quad\quad\ x \ge 0 \\
		\int_0^x e_\lambda(t) dt \quad x \gt 0
	\end{cases}
$$

Schreibe $X \sim \text{Exp}(\lambda)$