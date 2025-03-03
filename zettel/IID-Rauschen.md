Sei $(X_t)_{n \in \mathbb{Z}}$ eine Folge [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängiger]] und identisch verteilter [[zettel/Zufallsvariable|Zufallsvariablen]], $\sigma^2 := \text{Var}[X_1]$ mit
- $\forall t \in \mathbb{Z} : \text{E}[X_t] = 0$
- $\forall t \in \mathbb{Z} : \text{Var}[X_t] = \sigma^2$

$(X_t)_{n \in \mathbb{Z}}$ ist eine [[zettel/Zeitreihe|Zeitreihe]] und wird als *IDD-Rauschen* bezeichnet.

Schreibe

$$
	(X_t)_{n \in \mathbb{N}} \sim \text{IDD}(0, \sigma^2)
$$

Sei $(x_n)_{n \in \mathbb{Z}} \in \mathbb{R}$.

Es gilt

$$
	\forall t \in \mathbb{Z}, x \in \mathbb{R} : P(X_{t+1} \le x \mid \forall s \in \mathbb{Z}, z \le t : X_s = x_s) = P(X_{t+1} \le x)
$$

und
- $(X_t)_{n \in \mathbb{N}}$ ist [[zettel/Weißes Rauschen|weißes Rauschen]]
- $(X_t)_{n \in \mathbb{N}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]
- $(X_t)_{n \in \mathbb{N}}$ ist [[zettel/Zeitreihe/Starke Stationarität|stark stationär]]