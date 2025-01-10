Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $h$ die maximale Anzahl an Lags, $\text{H} : (X_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2), \text{K} : (X_t)_{t \in \mathbb{Z}} \not\sim \text{WN}(0, \sigma^2)$, $\alpha$ ein vorgegebenes Testniveau.

Es gilt

$$
	\sqrt{n}(\hat{\rho}(h) - \rho(h)) \overset{V}{\longrightarrow} \mathcal{N}(0, W)
$$

und
- $\forall h \in \mathbb{R}_0^+ : \rho(h) = 0$, falls $\text{H}$ gültig ist

Verwerfe $\text{H}$, falls

$$
	\sum_{i=1}^h \mathbb{1}\left( |\hat{\rho}(i)| \gt q_{1 - \frac{1}{2}} \right) \gt \lfloor \alpha h \rfloor
$$