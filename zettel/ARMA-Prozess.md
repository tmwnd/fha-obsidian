Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $(\phi_i)_{i \in \{ 1, \dots, p \}}, (\vartheta_i)_{i \in \{ 1, \dots, q \}} \in \mathbb{R}$ Folgen und
- einem sogenannten ein AR-Polynom $\phi : \mathbb{R} \to \mathbb{R}$ definiert als

$$
	\forall x \in \mathbb{R} : \phi(x) := \sum_{i \in \{ 1, \dots p \}} \phi_i x^i
$$

- einem sogenannten ein MA-Polynom $\vartheta : \mathbb{R} \to \mathbb{R}$ definiert als

$$
	\forall x \in \mathbb{R} : \vartheta(x) := \sum_{i \in \{ 1, \dots q \}} \vartheta_i x^i
$$

mit
- $\phi : \mathbb{R} \to \mathbb{R}$ und $\vartheta : \mathbb{R} \to \mathbb{R}$ haben keine gemeinsamen Nullstellen

Eine [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{R}}$ heißt *Autoregressiver Moving Average Prozess (ARMA-Prozess) der Ordnungen $p$ und $q$* falls

$$
	\forall t \in \mathbb{Z} : X_t - \sum_{i=1}^p \phi_i X_{t-i} = \varepsilon_t + \sum_{i=1}^q \vartheta_i \varepsilon_{t-i}
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)
$$