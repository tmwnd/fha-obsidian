Sei $(\epsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $\alpha \in \mathbb{R}$.

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Moving Average Prozess erster Ordnung* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \epsilon_t + \alpha \cdot \epsilon_{t-1}
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(1)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \mu_t = 0$
- $(X_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]