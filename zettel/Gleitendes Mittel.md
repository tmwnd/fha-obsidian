Sei $(X_t)_{t \in \mathbb{N}}$ eine [[zettel/Zeitreihe|Zeitreihe]].

Das *gleitende Mittel* $(\hat{\mu}_t)_{t \in \mathbb{N}}$ mit der Bandbreite $t \in \mathbb{N}$ ist definiert als

$$
	\forall t \in \mathbb{N} : \hat{\mu}_t := \frac{1}{2b+1} \sum_{i=t-b}^{t+b} X_i
$$

Das gleitende Mittel ist der Schätzer für das Signal eines [[zettel/Additives Zerlegungsmodell|additives Zerlegungsmodells]].