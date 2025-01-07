Sei $(X_t)_{t \in \mathbb{Z}}$ eine nicht-[[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $\mu := \mu_0$, $\hat{\sigma}^2 \in \mathbb{R}_0^+$ mit
- $\forall t \in \mathbb{Z} : \mu_t = \mu$

Der [[zettel/Schätzer|Schätzer]] $(\hat{\mu}_n)_{n \in \mathbb{N}}$ für $\mu$ ist definiert als

$$
	\forall n \in \mathbb{N} : \hat{\mu}_n := \frac{1}{n} \sum_{t=1}^n X_t
$$

Es gilt

$$
	\sqrt{n}(\hat{\mu} - \mu) \overset{V}{\longrightarrow} \mathcal{N}(0, \hat{\sigma}^2)
$$