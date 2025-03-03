Sei $(X_t)_{t \in \mathbb{N}}$ eine [[zettel/Zeitreihe|Zeitreihe]].

Das *gleitende Mittel* $(\hat{\mu}_t)_{t \in \mathbb{N}}$ von $(X_t)_{t \in \mathbb{N}}$ mit der Bandbreite $b \in \mathbb{N}$ ist definiert als

$$
	\forall t \in \mathbb{N} : \hat{\mu}_t := \frac{1}{2b+1} \sum_{s=t-b}^{t+b} X_s
$$

Das gleitende Mittel ist der Schätzer für das Signal eines [[zettel/Additives Zerlegungsmodell|additives Zerlegungsmodells]].

Es gilt
- $(\hat{\mu}_t)_{t \in \mathbb{N}}$ entspricht [[zettel/_edges/Nadaraya-Watson-Schätzer Additives Zerlegungsmodell Signal|Nadaraya-Watson-Schätzer]] mit dem Kern $K : \mathbb{R} \to \mathbb{R}$ definiert als

$$
	\forall x \in X_1 : K(x) = 1
$$