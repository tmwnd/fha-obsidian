Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwache stationäre]] [[zettel/Zeitreihe|Zeitreihe]] mit
- $\gamma(0) \gt 0$

Es existieren die [[zettel/Zeitreihe|Zeitreihen]] $(V_t)_{t \in \mathbb{Z}}$, $(Z_t)_{t \in \mathbb{Z}}$ und die Folge $(\psi_i)_{i \in \mathbb{N}_0} \in \mathbb{R}$ mit
- $\psi_0 = 1$
- $\sum_{i=1}^\infty \psi_i^2 \lt \infty$

sodass

$$
	\forall t \in \mathbb{Z} : V_t + \sum_{i=0}^\infty \psi_i Z_{t-i}
$$

Es gilt
- $(V_t)_{t \in \mathbb{Z}}$ ist [[zettel/Zeitreihe/Deterministisch|deterministisch]]
- $(U_t)_{t \in \mathbb{Z}}$ ist nicht-[[zettel/Zeitreihe/Deterministisch|deterministisch]]
- $Z \sim \text{WN}(0, \sigma^2)$
- $\forall s, t \in \mathbb{Z} : \text{Cov}[Z_t, V_s] = 0$

Falls $\forall t \in \mathbb{Z} : V_t = 0$, ist $(X_t)_{t \in \mathbb{Z}}$ ein [[zettel/Linearer Prozess|Linearer Prozess]].