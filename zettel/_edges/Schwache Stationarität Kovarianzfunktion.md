Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $\mu := \mu_0$ mit
- $\forall t \in \mathbb{Z} : \mu_t = \mu$

und $((Y_t^{(h)})_{t \in \mathbb{Z}})_{h \in \mathbb{Z}}$ eine Folge von [[zettel/Zeitreihe|Zeitreihen]] definiert als

$$
	\forall h, t \in \mathbb{Z} : Y_t^{(h)} := X_{t+h}X_t
$$

und $(\mu^{(h)})_{h \in \mathbb{Z}}$ eine Folge definiert als

$$
	\forall h \in \mathbb{Z} : \mu^{(h)} := \text{E}\left[ Y_0^{(h)} \right]
$$

$(X_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]], falls

$$
	\forall h, t \in \mathbb{Z} : \text{E}\left[ Y_t^{(h)} \right] = \mu^{(h)}
$$