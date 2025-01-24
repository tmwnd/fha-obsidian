Sei $(X_t)_{t \in \mathbb{Z}}$ ein [[zettel/Linearer Prozess|Linearer Prozess]] von $(\varepsilon_t)_{t \in \mathbb{Z}}$ [[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]] mit
- $\forall t \in \mathbb{Z} : \text{E}[\varepsilon_t] = 0$

Die [[zettel/ACVF|ACVF]] $\gamma : \mathbb{Z} \to \mathbb{R}$ für $(X_t)_{t \in \mathbb{N}}$ ist gegeben durch

$$
	\forall h \in \mathbb{Z} : \gamma(h) = \sum_{i \in \mathbb{Z}} \sum_{j \in \mathbb{Z}} \psi_i\psi_j \text{Cov}[\varepsilon_{h+i-j}, \varepsilon_0]
$$