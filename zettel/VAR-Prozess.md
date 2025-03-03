Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Zeitreihe/Mehrdimensionale Schwache Stationarität|mehrdimensional schwach stationäre]] [[zettel/Vektorwertige Zeitreihe|vektorwertige Zeitreihe]] mit Werten in $\mathbb{R}^k$, $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{VWN}(0, \Sigma)$, $\Phi \in \mathbb{R}^{p \times k}$.

$(X_t)_{t \in \mathbb{Z}}$ heißt *Vektorwertiger Autoregressiver Prozess (VAR-Prozess) der Ordnung $p$*, falls

$$
	\forall t \in \mathbb{Z} : X_t = \varepsilon_t + \sum_{i=1}^p \Phi_i B^i(X_t)
$$

Schreibe

$$
	(X_t)_{t \in \mathbb{Z}} \sim \text{VAR}(p)
$$

Es gilt
- $\text{VAR}(p)$ mit Werten in $\mathbb{R}^k$ $\equiv$ $\text{VAR}(1)$ mit Werten in $\mathbb{R}^{k \cdot p}$