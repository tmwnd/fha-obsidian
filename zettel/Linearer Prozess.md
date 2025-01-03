Sei $(\epsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $(\psi_i)_{i \in \mathbb{Z}} \in \mathbb{R}$ mit
- $\sum_{i=-\infty}^\infty |\psi_i| \lt \infty$

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Linearer Prozess* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \sum_{i=-\infty}^\infty \psi_i B^i(\epsilon_t)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \mu_t = 0$
- $(X_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]

Falls $\forall i \lt 0 : \psi_i = 0$ gilt
- $(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(\infty)$