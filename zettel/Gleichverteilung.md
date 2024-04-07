---
title: Gleichverteilung
type: example
---

Seien $-\infty \lt a \lt b \lt +\infty$ und die $\lambda$-[[zettel/λ-Dichte|Dichte]] $r : [a, b] \to \mathbb{R}_+$ konstant mit
- $r \equiv \frac{1}{b - a}$ auf $[a, b]$

Sei $x \in \mathbb{R}$.

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] einer reelwertigen [[zettel/Zufallsvariable|Zufallsvariable]] $X$ heißt *gleich-* bzw. *rechteckverteilt*, falls

$$
	F(x) = P(x \le x) = \begin{cases}
		0, & x \le a \\
		\int_a^x r(t) dt, & a \lt x \le b \\
		1, & x \gt b
	\end{cases} = \begin{cases}
		0, & x \le a \\
		\frac{x - a}{b - a}, & a \lt x \le b \\
		1, & x \gt b
	\end{cases}
$$

Schreibe
- $X \sim \mathcal{R}(a, b)$.

---

Sei $X \sim \mathcal{R}(a, b)$ eine [[zettel/Zufallsvariable|Zufallsvariable]].

Es gilt
- Der [[zettel/Zufallsvariable Erwartungswert|Erwartungswert]] von $X$ ist $E[X] = \frac{a + b}{2}$
- Die [[zettel/Zufallsvariable Varianz|Varianz]] von $X$ ist $\text{Var}(X) = \frac{(b - a)^2}{12}$