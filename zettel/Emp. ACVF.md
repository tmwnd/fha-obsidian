Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine nicht-[[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $(\hat{\mu}_t)_{t \in \{ 1, \dots, n \}}$ ein [[zettel/Schätzer|Schätzer]] für $(\mu_t)_{t \in \{ 1, \dots, n \}}$.

Die *empirische [[zettel/ACVF|Autokovarianzfunktion]] (emp. ACVF)* $\hat{\gamma} : \mathbb{Z} \to \mathbb{R}$ ist definiert als

$$
	\forall h \in \mathbb{Z}, |h| \lt n : \hat{\gamma}(h) := \frac{1}{n} \sum_{t=1}^{n-|h|} (X_{t+|h|} - \hat{\mu}_t) \cdot (X_t - \hat{\mu}_s)
$$