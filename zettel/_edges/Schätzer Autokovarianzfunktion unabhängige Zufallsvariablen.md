Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $(\hat{\mu}_t)_{t \in \{ 1, \dots, n \}}$ ein [[zettel/Schätzer|Schätzer]] für $(\mu_t)_{t \in \{ 1, \dots, n \}}$.

Die [[zettel/Schätzer|Schätzer]] der [[zettel/ACVF|ACVF]] $\hat{\gamma} : \mathbb{Z} \to \mathbb{R}$ für $(X_t)_{t \in \{ 1, \dots, n \}}$ ist definiert als

$$
	\forall h \in \mathbb{N}_0 : \hat{\gamma}(h) := \begin{cases}
		\frac{1}{n} \sum_{t=1}^n (X_t - \hat{\mu}_t)^2 & h = 0 \\
		0 & \text{sonst}
	\end{cases}
$$