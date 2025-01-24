Sei $(X_t)_{t \in \{ 1, \dots, n \}} := (\mu_t + \varepsilon_t)_{t \in \{ 1, \dots, n \}}$ ein [[zettel/Additives Zerlegungsmodell|additives Zerlegungsmodell]], $K : \mathbb{R} \to \mathbb{R}$ ein Kern mit
- $\text{Tr}(K) = [-1, 1]$

Der *Nadaraya-Watson-Schätzer* $(\hat{\mu}_t)_{t \in \{ 1, \dots, n \}}$ des *Signals* $(\mu_t)_{t \in \{ 1, \dots, n \}}$ von $(X_t)_{t \in \{ 1, \dots, n \}}$ mit der Bandbreite $b \in \mathbb{N}$ ist definiert als

$$
	\forall t \in \{ 1, \dots, n \} : \hat{\mu}_t := \frac{\sum_{s=1}^n X_s K(\frac{t-s}{b})}{\sum_{s=1}^n K(\frac{t-s}{b})}
$$