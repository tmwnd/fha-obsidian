Seien $-\infty \lt a \lt b \lt +\infty$ und die $\lambda$-[[lambda-Dichte|Dichte]] $r : [a, b] \to \mathbb{R}_+$ konstant mit
- $r \equiv \frac{1}{b - a}$ auf $[a, b]$

Sei $x \in \mathbb{R}$.

Die [[Verteilungsfunktion]] einer reelwertigen [[Zufallsvariable]] $X$ heißt *gleich-* bzw. *rechteckverteilt*, falls

$$
	F(x) = P(x \le x) = \begin{cases}
		0, \quad\quad\quad\quad\ x \le a \\
		\int_a^x r(t) dt, \quad a \lt x \le b \\
		1, \quad\quad\quad\quad\ x \gt b
	\end{cases} = \begin{cases}
		0, \quad\quad\ x \le a \\
		\frac{x - a}{b - a}, \quad a \lt x \le b \\
		1, \quad\quad\ x \gt b
	\end{cases}
$$

Schreibe $X \sim \mathcal{R}(a, b)$.

---

Sei $X \sim \mathcal{R}(a, b)$ eine [[Zufallsvariable]].

Es gilt
- Der [[Erwartungswert]] ist $E[X] = \frac{a + b}{2}$
- Die [[Varianz]] ist $\text{Var}(X) = \frac{(b - a)^2}{12}$