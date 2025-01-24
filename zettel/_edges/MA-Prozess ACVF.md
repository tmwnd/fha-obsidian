Sei $(X_t)_{t \in \mathbb{N}} \sim \text{MA}(q)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$.

Die [[zettel/ACVF|ACVF]] $\gamma : \mathbb{Z} \to \mathbb{R}$ für $(X_t)_{t \in \mathbb{N}}$ ist gegeben durch

$$
	\forall h \in \mathbb{Z} : \gamma(h) = \begin{cases}
		\sum_{i=0}^{q-|h|} \vartheta_i\vartheta_{i+|h|} & |h| \le q \\
		0 & |h| \gt q
	\end{cases}
$$