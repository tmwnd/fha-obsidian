Sei $(X_t)_{t \in \mathbb{Z}}$ eine nicht-[[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $\mu := \mu_0$, $(\mu_n)_{n \in \mathbb{N}}$ ein [[zettel/Schätzer|Schätzer]] für $\mu$ mit
- $\forall t \in \mathbb{Z} : \mu_t = \mu$

Die *empirische [[zettel/ACVF|Autokovarianzfunktion]] (emp. ACVF)* $\hat{\gamma} : \mathbb{Z} \to \mathbb{R}$ ist definiert als

$$
	\forall h \in \mathbb{Z} : \hat{\gamma}(h) := \frac{1}{n} \sum_{t=1}^{n-|h|} (X_{t+|h|} - \hat{\mu}_n) \cdot (X_t - \hat{\mu}_n)
$$