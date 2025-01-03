Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]].

Die *Autokovarianzfunktion (ACVF)* $\gamma : \mathbb{Z} \to \mathbb{R}$ für $(X_t)_{t \in \mathbb{Z}}$ ist definiert als

$$
	\forall h \in \mathbb{Z} : \gamma(h) := \gamma(h, 0)
$$

und beschreibt $\forall t \in \mathbb{Z}$ die lineare Abhängigkeit zwischen $X_{t+h}$ und $X_t$.

Es gilt
- $\forall t, h \in \mathbb{Z} : \gamma(h) = \gamma(t+h, t)$