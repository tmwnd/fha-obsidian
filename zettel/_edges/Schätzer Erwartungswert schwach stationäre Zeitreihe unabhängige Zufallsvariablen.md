Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $\mu := \mu_0$, $\sigma^2 := \gamma(0)$ mit
- $\forall t \in \mathbb{Z} : \mu_t = \mu$
- $\forall t \in \mathbb{Z} : \text{Var}[X_t] = \sigma^2$

Der Schätzer $(\hat{\mu}_n)_{n \in \mathbb{N}}$ für $\mu$ ist definiert als

$$
	\forall n \in \mathbb{N} : \hat{\mu}_n := \frac{1}{n} \sum_{t=1}^n X_t
$$

Es gilt

$$
	\sqrt{n}(\hat{\mu} - \mu) \overset{V}{\longrightarrow} \mathcal{N}(0, \sigma^2)
$$