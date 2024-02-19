Sei $p \in [0, 1]$ und $X$ eine reelle [[Zufallsvariable]].

$\xi_p \in \mathbb{R}$ heißt *$p$-Quantil*  von $X$ bzw. $P^X$, falls

$$
	P(X \lt \xi_p) \le p \le P(X \le \xi_p)
$$

---

Sei $p \in [0, 1]$ und $X$ eine reelle [[Zufallsvariable]].

Die Menge der $p$-Quantile von $X$ ist definiert als das Interval $[\xi_p^-, \xi_P^+]$ mit
- $\xi_p^- = \inf\{ x \in \mathbb{R} : P(X \le x) \ge p \}$
- $\xi_p^+ = \sup\{ x \in \mathbb{R} : P(X \ge x) \ge 1 - p \} = \sup\{ x \in \mathbb{R} : P(X \lt x) \le p \}$

$\xi_p$ ist eindeutig bestimmt, falls die [[Verteilungsfunktion]] $F(X)$ den Wert $p$ höchstens einmal annimt.

---

Ein $\frac{1}{2}$-Quantil heißt *Median* von $X$.