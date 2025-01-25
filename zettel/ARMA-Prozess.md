Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $\phi \in \mathbb{R}^p$, $\vartheta \in \mathbb{R}^q$ und
- $\phi : \mathbb{R} \to \mathbb{R}$ ein sogenanntes AR-Polynom definiert als

$$
	\forall x \in \mathbb{R} : \phi(x) := \sum_{i=1}^p \phi_i x^i
$$

- $\vartheta : \mathbb{R} \to \mathbb{R}$ ein sogenanntes MA-Polynom definiert als

$$
	\forall x \in \mathbb{R} : \vartheta(x) := \sum_{i=1}^q \vartheta_i x^i
$$

mit
- $\phi$ und $\vartheta$ haben keine gemeinsamen Nullstellen

Eine [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{R}}$ heißt *Autoregressiver Moving Average Prozess (ARMA-Prozess) der Ordnungen $p$ und $q$*, falls

$$
	\forall t \in \mathbb{Z} : X_t = \varepsilon_t + \sum_{i=1}^p \phi_i B^i(X_t) + \sum_{i=1}^q \vartheta_i B^i(\varepsilon_t)
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)
$$