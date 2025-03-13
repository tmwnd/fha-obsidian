Sei $(X, d)$ ein [[zettel/Metrischer Raum|metrischer Raum]].

Eine Folge $(x_n)_{n \in \mathbb{N}} \in X$ heißt *Cauchyfolge*, falls

$$
	\forall \varepsilon \gt 0 \ \exists N \in \mathbb{N} \ \forall m, n \ge N : d(x_n, x_m) \lt \varepsilon
$$

bzw.

$$
	\lim_{n, m \to \infty} d(x_n, x_m) = 0
$$