Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine unkorrelierte [[zettel/Zeitreihe|Zeitreihe]], $\sigma^2 := \text{Var}[X_0]$.

$(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ heißt *weißes Rauschen*, falls
- $\forall t \in \mathbb{Z} : \text{E}[X_t] = 0$
- $\forall t \in \mathbb{Z} : \text{Var}[X_t] = \sigma^2$
- $\forall t, s \in \mathbb{Z}, t \ne s : \text{Cov}[X_t, X_s] = 0$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)
$$

Es gilt
- $(X_t)_{t \in \mathbb{R}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach staionär]]