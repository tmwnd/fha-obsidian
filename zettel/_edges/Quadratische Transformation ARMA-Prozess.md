Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, \sigma^2)$ und
- $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert als

$$
	\forall t \in \mathbb{Z} : X_t := t^2 + \varepsilon_t
$$

- $(Y_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert als

$$
	\forall t \in \mathbb{Z} : Y_t := \nabla^2 X_t - 2 = X_t - 2 \cdot B(X_t) + B^2(X_t) - 2 = 2 + (\varepsilon_t - 2 \cdot B(\varepsilon_t) + B^2(\varepsilon_t)) - 2 = \varepsilon_t - 2 \cdot B(\varepsilon_t) + B^2(\varepsilon_t)
$$

Es gilt
- $(X_t)_{t \in \mathbb{Z}}$ ist nicht-[[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]
- $(Y_t)_{t \in \mathbb{Z}} \sim \text{MA}(2)$
- $(Y_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]