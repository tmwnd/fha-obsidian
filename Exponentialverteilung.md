Sei $\mu \in (0, \infty)$, $t \gt 0$ und die $\lambda$-[[lambda-Dichte|Dichte]] $e_\lambda$ definiert als

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

---

Sei $X \sim \text{Exp}(\lambda)$ eine [[Zufallsvariable]].

Es gilt
- Der [[Erwartungswert]] ist $E[X] = \frac{1}{\lambda}$
- Die [[Varianz]] ist $\text{Var}(X) = \frac{1}{\lambda^2}$