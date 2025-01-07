Sei $(X_t)_{t \in \{ 1, \dots, n \}} = (\mu_t + s_t + \epsilon_t)_{t \in \{ 1, \dots, n \}}$ ein  [[zettel/Additives Zerlegungsmodell mit saisonaler Komponente|additives Zerlegungsmodell mit saisonaler Komponente]] mit bekannter Periodenlänge $d$ mit
- $m := \frac{n}{d}$

Der [[zettel/Schätzer|Schätzer]] $(\hat{s}_k)_{t \in \{ 1, \dots, n \}}$ der saisonalen Komponente $(s_k)_{t \in \{ 1, \dots, n \}}$ von $(X_t)_{t \in \{ 1, \dots, n \}}$ ist definiert als

$$
	\forall k \in \{ 1, \dots, d \} : \hat{s}_k := \frac{1}{m} \sum_{i=1}^m X_{k+i \cdot d}
$$

Es gilt
- $\forall k \in \mathbb{N} : \hat{s}_k = \hat{s}_{k \mod d}$