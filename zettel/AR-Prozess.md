
Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$, $\phi \in \mathbb{R}^p$.

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver Prozess (AR-Prozess)* und ist definiert als

$$
	\forall t \in \mathbb{Z} : X_t := \varepsilon_t + \sum_{i=1}^p \phi_i \cdot X_{t-i}
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(p)
$$

Es gilt
- $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, 0)$