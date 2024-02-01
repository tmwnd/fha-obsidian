Sei $n \in \mathbb{N}$, $(k_i)_{i \in \mathbb{N}} \in \mathbb{N}_0$, $p_i \in [0, 1]$ mit
- $\sum_{i=1}^n k_i = n$

Sei $x \in \mathbb{R}^d$.

Die [[Verteilungsfunktion]] eines reelwertigen $d$-dimensionalen [[Zufallsvariable|Zufallsvektors]] $X$ heißt *multinomialverteilt*, falls

$$
	P(X_1 = x_1, \dots, X_d = x_d) = \frac{n!}{\Pi_{n=1}^dk_i!}\Pi_{i=1}^dp_i^{k_i}
$$

Schreibe $X \sim \mathfrak{M}(n, p_1, \dots, p_d)$