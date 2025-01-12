Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, \sigma^2)$ und
- die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{Z}}$ definiert als

$$
	\forall t \in \mathbb{Z} : X_t := t^2 + \varepsilon_t
$$

- die [[zettel/Zeitreihe|Zeitreihe]] $(Y_t)_{t \in \mathbb{Z}}$ definiert als

$$
	\forall t \in \mathbb{Z} : Y_t := \nabla^2 X_t - 2 = X_t - 2 \cdot X_{t-1} + X_{t-2} - 2 = 2 + (\varepsilon_t - 2 \cdot \varepsilon_{t-1} + \varepsilon_{t-2}) - 2 = \varepsilon_t - 2 \cdot \varepsilon_{t-1} + \varepsilon_{t-2}
$$

Es gilt
- $(X_t)_{t \in \mathbb{Z}}$ ist nicht-[[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]
- $(Y_t)_{t \in \mathbb{Z}} \sim \text{MA}(2)$
- $(Y_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]