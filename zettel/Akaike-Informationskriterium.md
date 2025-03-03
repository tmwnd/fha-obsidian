Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $\vartheta \in \Theta \subseteq \mathbb{R}^k$ der Modellparameter, $f((c_t)_{t \in \mathbb{Z}} \mid \vartheta)$ die gemeinsame Dichte von $(X_t)_{t \in \mathbb{Z}}$ und
- $L : \Theta \to \mathbb{R}$ die Likelihood-Funktion definiert als

$$
	\forall \vartheta \in \Theta : L(\vartheta) := f((x_t)_{t \in \mathbb{Z}} \mid \vartheta)
$$

- $\hat{\vartheta}$ der ML-Schätzer für $\vartheta$ definiert als

$$
	\hat{\vartheta} = \underset{\vartheta \in \Theta}{\arg\max} L(\vartheta)
$$

Das *Akaike-Informationskriterium* $\text{AIK}$ für $\hat{\vartheta}$ ist definiert als

$$
	\text{AIK} := 2k - 2\log(L(\hat{\vartheta}))
$$

Es gilt
- $k = p + q$, falls $(X_t)_{t \ni \mathbb{Z}} \sim \text{ARMA}(p, q)$