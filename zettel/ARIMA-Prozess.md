Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$, $d \in \mathbb{N}_0$ und
- die [[zettel/Zeitreihe|Zeitreihe]] $(Y_t)_{t \in \mathbb{Z}}$ definiert über

$$
	\forall t \in \mathbb{Z} : X_t : \nabla^d Y_t
$$

$(Y_t)_{t \in \mathbb{Z}}$ heißt *Autoregressiver integrierter Moving Average Prozess der Ordnung $d$*.

Schreibe

$$
	(Y_t)_{t \in \mathbb{Z}} \sim \text{ARIMA}(p, d, q)
$$

Es gilt

$$
	\forall t \in \mathbb{Z} : \sum_{i=1}^p \phi \nabla^d Y_t = \sum_{i=1}^q \vartheta\varepsilon_t
$$