Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]], $m \gt \max(p, q)$, $\tilde{\phi}$ der [[zettel/Yule-Walker-Schätzer|Yule-Walker-Schätzer]] für $\phi$ mit der Annahme $(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(m)$ und
- $(\hat{\varepsilon}_t)_{t \in \mathbb{Z}}$ ein Schätzer für die Residuen von $(X_t)_{t \in \mathbb{Z}}$ definiert als

$$
	\forall t \in \mathbb{Z} : \hat{\varepsilon_t} := X_t - \sum_{i=1}^m \tilde{\phi}_i B^i(X_t)
$$

- $S : \mathbb{R}^{p+q} \to \mathbb{R}$ definiert als

$$
	\forall \beta \in \mathbb{R}^{p+q} : S(\beta) := \sum_{t=m+1+q}^n \left( X_t - \sum_{i=1}^p \beta_i B^i(X_t) - \sum_{i=1}^q \beta_{p+i} \hat{\varepsilon}_{t-i} \right)^2
$$

Der *Hannan-Rissanen-Schätzer* $\hat{\phi}, \hat{\vartheta}, \hat{\sigma}^2$ für $\phi, \vartheta, \sigma^2$ ist definiert als

$$
	\hat{\beta} := \underset{\beta \in \mathbb{R}^{p+q}}{\arg\min} S(\beta)
$$

mit
- $\hat{\phi} = (\beta_i)_{i \in \{ 1, \dots, p \}}$
- $\hat{\vartheta} = (\beta_{p+i})_{i \in \{ 1, \dots, q \}}$

bzw.

$$
	\hat{\sigma}^2 = \frac{1}{n-m-q} S(\hat{\beta})
$$