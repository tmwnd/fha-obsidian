---
type: assignment
---

1. Es sei $X$ eine reelle Zufallsvariable mit der Dichte
	
	$$
		f(x) = \begin{cases}
			\frac{1}{\pi\sqrt{1-x^2}}, & -1 \lt x \lt 1 \\
			0, & \text{sonst}
		\end{cases}
	$$
	
	Gesucht ist $\text{Var}(X)$.

^1

2. Es sei $f : [0, 1] \to \mathbb{R}$ stetig und $X_{n, p} \sim \mathfrak{B}(n, p)$, $p \in [0, 1]$, $n \in \mathbb{N}$.
	Beweisen Sie mit Hilfe der Chebyshevschen Ungleichung, dass Bernstein-Polynome
	
	$$
		f_n(p) = E\left( f\left( \frac{1}{n}X_{n, p} \right) \right) = \sum_{k=0}^n f\left( \frac{k}{n} \right)\binom{n}{k}p^k(1-p)^{n-k}
	$$
	
	gleichmäßig auf dem Intervall $[0, 1]$ gegen $f$ konvergiert.
	
	
	Es seien $P, Q$ Wahrscheinlichkeitsmaße auf $(\mathbb{R}^k, \mathfrak{B}^k)$.
	Zeigen Sie, dass $P$ und $Q$ genau dann gleich sind, wenn für jede stetige und beschränkte Funktion $f : \mathbb{R}^k \to \mathbb{R}$
	
	$$
		\int f dP = \int f dQ
	$$
	
	gilt.

^2