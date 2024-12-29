Sei $(X_t)_{t \in \{ 1, \dots, n \}} = (\mu_t + \epsilon_t)_{t \in \{ 1, \dots, n \}}$ ein [[zettel/Additives Zerlegungsmodell|additives Zerlegungsmodell]], $K : \mathbb{R} \to \mathbb{R}$ ein Kern mit
- $\text{Tr}(K) = [-1, 1]$

Die *lokal lineare Schätzung* $(\hat{\mu}_t, \hat{\mu}_t')_{t \in \{ 1, \dots, n \}}$ des *Signals* $(\mu_t)_{t \in \{ 1, \dots, n \}}$ bzw. der Ableitung des Signals $(\mu_t')_{t \in \{ 1, \dots, n \}}$ von $(X_t)_{t \in \{ 1, \dots, n \}}$ ist definiert als

$$
	\forall t \in \{ 1, \dots, n \} : (\hat{\mu}_t, \hat{\mu}_t') := \underset{\beta_0, \beta_1}{\arg\min} \sum_{i=1}^n \left( X_i - \beta_0 - \beta_1 \cdot (i - t) \right)^2 K\left( \frac{i-t}{b} \right)
$$