Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$, $d \in \mathbb{N}_0$ und
- $(Y_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert über

$$
	\forall t \in \mathbb{Z} : X_t : \nabla^d Y_t
$$

$(Y_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver Integrierter Moving Average Prozess der Ordnung $d$*.

Schreibe

$$
	(Y_t)_{t \in \mathbb{Z}} \sim \text{ARIMA}(p, d, q)
$$

Es gilt

$$
	\forall t \in \mathbb{Z} : \nabla^d Y_t = \varepsilon_t + \sum_{i=1}^p \phi_i \nabla^d Y_{t-1} + \sum_{i=1}^q \vartheta_i B^i(\varepsilon_t)
$$