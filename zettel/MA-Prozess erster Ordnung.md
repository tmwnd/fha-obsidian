Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $\phi \in \mathbb{R}$.

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Moving Average Prozess (MA-Prozess) erster Ordnung* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \varepsilon_t + \phi \cdot \varepsilon_{t-1}
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(1)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \mu_t = 0$
- $(X_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]
- $(X_t)_{t \in \mathbb{Z}}$ ist ein [[zettel/Linearer Prozess|Linearer Prozess]] mit $\psi_i = \begin{cases} 1 & i=0 \\ \phi & i=1 \\ 0 & \text{sonst} \end{cases}$