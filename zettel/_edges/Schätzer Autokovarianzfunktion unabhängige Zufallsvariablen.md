Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $\mu := \mu_0$, $(\mu_n)_{n \in \mathbb{N}}$ ein Schätzer für $\mu$ mit
- $\forall t \in \mathbb{Z} : \mu_t = \mu$

Die Schätzer der [[zettel/Autokovarianzfunktion (ACVF)|ACVF]] $\hat{\gamma} : \mathbb{Z} \to \mathbb{R}$ ist definiert als

$$
	\forall h \in \mathbb{Z} : \hat{\gamma}(h) := \begin{cases}
		0 & |h| \ge 1 \\
		\frac{1}{n} \sum_{t=1}^n (X_t - \hat{\mu}_n)^2 & h = 0
	\end{cases}
$$