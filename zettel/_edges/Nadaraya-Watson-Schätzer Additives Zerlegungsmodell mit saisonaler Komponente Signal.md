Sei $(X_t)_{t \in \{ 1, \dots, n \}} = (\mu_t + s_t + \varepsilon_t)_{t \in \{ 1, \dots, n \}}$ ein  [[zettel/Additives Zerlegungsmodell mit saisonaler Komponente|additives Zerlegungsmodell mit saisonaler Komponente]] mit bekannter Periodenlänge $d$, $K : \mathbb{R} \to \mathbb{R}$ ein Kern mit
- $\text{Tr}(K) = [-1, 1]$

Der *Nadaraya-Watson-Schätzer* $(\hat{\mu}_t)_{t \in \mathbb{N}}$ des *Signals* $(\mu_t)_{t \in \{ 1, \dots, n \}}$ von $(X_t)_{t \in \mathbb{N}}$ mit der Bandbreite $\lfloor \frac{d}{2} \rfloor$ ist definiert als

$$
	\forall t \in \{ 1, \dots, n \} : \hat{\mu}_t := \frac{\sum_{i=1}^n X_i K(\frac{t-1}{\frac{d}{2}})}{\sum_{i=1}^n K(\frac{t-1}{\frac{d}{2}})}
$$

Falls $K$ gleichmäßig, gilt

$$
	\forall t \in \mathbb{N} : \hat{\mu}_t := \frac{1}{d} \sum_{i=t-\lfloor \frac{d}{2} \rfloor}^{t+\lfloor \frac{d}{2} \rfloor} X_i
$$