Seien $(X_t)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] und identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $\sigma^2 \in \mathbb{R}$ mit
- $\forall t \in \mathbb{N} : \text{E}[X_t] = 0$
- $\forall t \in \mathbb{N} : \text{Var}[X_t] = \sigma^2$

$(X_t)_{n \in \mathbb{N}}$ ist eine [[zettel/Zeitreihe|Zeitreihe]] und wird als *IDD-Rauschen* bezeichnet.

Schreibe

$$
	(X_t)_{n \in \mathbb{N}} \sim \text{IDD}(0, \sigma^2)
$$

Sei $(x_n)_{n \in \mathbb{N}} \in \mathbb{R}$.

Es gilt

$$
	\forall t \in \mathbb{N} : P(X_{t+1} \le x \mid \forall i \le t : X_i = x_i) = P(X_{t+1} \le x_{t+1})
$$

und
- $(X_t)_{n \in \mathbb{N}}$ ist [[zettel/Weißes Rauschen|weißes Rauschen]]
- $(X_t)_{n \in \mathbb{N}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]