Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $\vartheta \in \Theta \subseteq \mathbb{R}^k$ der Modellparameter, $f((x_t)_{t \in \mathbb{Z}} \mid \vartheta) := \prod_{i \in \mathbb{Z}} f(x_i \mid \vartheta)$ die gemeinsame Dichte von $(X_t)_{t \in \mathbb{Z}}$.

Der *Maximum-Likelihood-Schätzer* $\hat{\vartheta}$ für $\vartheta$ ist definiert als

$$
	\hat{\vartheta} := \underset{\vartheta \in \Theta}{\arg\max} f((x_t)_{t \in \mathbb{Z}} \mid \vartheta)
$$