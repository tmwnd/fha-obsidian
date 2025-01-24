Sei $(\varepsilon_t)_{t \in \mathbb{N}} \sim \text{IID}(0, \sigma^2)$.

Die [[zettel/Zeitreihe|Zeitreihe]] $(X_t)_{t \in \mathbb{N}}$ heißt *Random Walk* und ist definiert als

$$
	\forall t \in \mathbb{N} : X_t := \sum_{s=1}^t \varepsilon_s
$$

Es gilt
- $\forall t \in \mathbb{N} : \text{E}[X_t] = \sum_{s=1}^t \text{E}[\varepsilon_s] = 0$
- $\forall t \in \mathbb{N} : \text{Var}[X_t] = \sum_{s=1}^t \text{Var}[\varepsilon_s] = t \cdot \sigma^2$
- $(X_t)_{t \in \mathbb{N}}$ ist nicht-[[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]