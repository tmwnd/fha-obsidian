Sei $(X_t)_{t \in \{ 1, \dots, n \}} = (\mu_t + s_t + \varepsilon_t)_{t \in \{ 1, \dots, n \}}$ ein  [[zettel/Additives Zerlegungsmodell mit saisonaler Komponente|additives Zerlegungsmodell mit saisonaler Komponente]].

Die *diskrete Fourier-Transformation* $(\hat{X}_f)_{f \in \{ 0, \dots, n-1 \}}$ von $(X_t)_{t \in \{ 1, \dots, n \}}$ ist definiert als

$$
	\forall f \in \{ 0, \dots, n-1 \} : \hat{X}_f := \sum_{t=0}^{n-1} X_{t+1} \cdot \exp\left( -2\pi i \frac{t \cdot f}{n} \right)
$$