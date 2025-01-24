Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $(\psi_i)_{i \in \mathbb{Z}} \in \mathbb{R}$ eine Folge mit
- $\sum_{i \in \mathbb{Z}} |\psi_i| \lt \infty$

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Linearer Prozess* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \sum_{i \in \mathbb{Z}} \psi_i B^i(\varepsilon_t)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \mu_t = 0$
- $(X_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]

und
- $(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(\infty)$, falls $\forall i \lt 0 : \psi_i = 0$