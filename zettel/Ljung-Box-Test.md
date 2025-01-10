Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $h$ die maximale Anzahl an Lags, $\text{H} : (X_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2), \text{K} : (X_t)_{t \in \mathbb{Z}} \not\sim \text{WN}(0, \sigma^2)$, $\alpha$ ein vorgegebenes Testniveau mit

$$
	Q_{LB} := n(n+2) \sum_{i=1}^h \frac{\hat{\rho}^2(i)}{n-i}
$$

Verwerfe $\text{H}$, falls

$$
	Q_{LB} \gt \chi_{1-\alpha}^2(h)
$$