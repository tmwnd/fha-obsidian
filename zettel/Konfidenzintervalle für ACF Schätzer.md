Sei $(X_t)_{t \in \mathbb{Z}}$ eine geeignete [[zettel/Zeitreihe|Zeitreihe]], $W \in \mathbb{R}^{h \times h}$ mit

$$
	\forall i, j \in \{ 1, \dots, h \} : W_{i, j} := \sum_{h=1}^\infty \prod_{\tau \in \{ i, j \}} (\rho(h + \tau) + \rho(h - \tau) - 2\rho(h)\rho(\tau))
$$

Es gilt

$$
	\sqrt{n}\left( (\hat{\rho}(i))_{i \in \{ 1, \dots, h \}}^T - (\rho(i))_{i \in \{ 1, \dots, h \}}^T \right) \overset{V}{\longrightarrow} \mathcal{N}(0, W)
$$