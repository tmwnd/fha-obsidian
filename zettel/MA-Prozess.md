Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $\vartheta \in \mathbb{R}^q$.

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Moving Average Prozess (MA-Prozess)* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \varepsilon_t + \sum_{i=1}^q \vartheta_i B^i(\varepsilon_t)
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(q)
$$

Es gilt
- $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(0, q)$