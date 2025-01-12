Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, \sigma^2)$ und
- die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ definiert als

$$
	\forall t \in \mathbb{Z} : X_t := t + \varepsilon_t
$$

- die [[zettel/Zeitreihe|Zeitreihe]] $(Y_t)_{t \in \mathbb{Z}}$ definiert als

$$
	\forall t \in \mathbb{Z} : Y_t := \nabla X_t - 1 = 1 + (\varepsilon_t - \varepsilon_{t-1}) - 1 = \varepsilon_t - \varepsilon_{t-1}
$$

Es gilt
- $(X_t)_{t \in \mathbb{Z}}$ ist nicht-[[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]
- $(Y_t)_{t \in \mathbb{Z}} \sim \text{MA}(1)$
- $(Y_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]