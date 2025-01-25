Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $\phi \in \mathbb{R}$.

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver Prozess (AR-Prozess) erster Ordnung* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \varepsilon_t + \phi \cdot B(X_t)
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(1)
$$

Es gilt
- $\forall t \in \mathbb{Z} : \mu_t = 0$
- $(X_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]

und
- $(X_t)_{t \in \mathbb{Z}}$ ist ein [[zettel/Linearer Prozess|Linearer Prozess]] mit $\psi_i = \begin{cases} \alpha^i & i \ge 0 \\ 0 & i \lt 0 \end{cases}$