Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]].

Die *Autokorrelationsfunktion (ACF)* $\rho : \mathbb{Z} \to \mathbb{R}$ für $(X_t)_{t \in \mathbb{Z}}$ ist definiert als

$$
	\forall h \in \mathbb{Z} : \rho(h) := \frac{\gamma(h)}{\gamma(0)}
$$

Es gilt

$$
	\forall t, h \in \mathbb{Z} : \rho(h) = \frac{\gamma(t+h, t)}{\text{Var}[X_t]}
$$