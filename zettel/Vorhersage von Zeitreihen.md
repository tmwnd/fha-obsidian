Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]] mit
- $\forall t \in \mathbb{Z} : \mu_t = 0$

und

$$
	M := \left\{ \sum_{i=1}^p \alpha_i X_{t-i} \mid \alpha \in \mathbb{R}^p \right\} = \text{span}((X_i)_{i \in \{ t-p, t \}})
$$

Die Vorhersage von $X_t$, $t \in \mathbb{Z}$ basierend auf den vergangenen $p \in \mathbb{Z}$ Werten $(X_i)_{i \in \{ t-p, t \}}$ ist mit $\beta \in \mathbb{R}^p$ definiert als

$$
	\hat{X}_t := P_M(X_t) = \sum_{i=1}^p \beta_i X_{t-i} \in M
$$

Es muss gelten

$$
	\forall \alpha \in \mathbb{R}^p : \text{E}\left[ (X_t - \hat{X}_t) \sum_{i=1}^p \alpha_i X_{t-i} \right] \implies \forall j \in \{ 1, \dots, p \} : 0 \overset{!}{=} \text{E}[(X_t - \hat{X}_t)X_{t-j}] = \gamma(j) - \sum_{i=1}^p \beta_i\gamma(|i-j|)
$$

Zur eindeutigen Bestimmung von $\hat{X}_t$ ist folgendes LGS zu lösen

$$
	\begin{pmatrix}
		\gamma(0) & \gamma(1) & \gamma(2) & \cdots & \gamma(p-1) \\
		\gamma(1) & \gamma(0) & \gamma(1) & \cdots & \gamma(p-2) \\
		\gamma(2) & \gamma(1) & \gamma(0) & \cdots & \gamma(p-3) \\
		\vdots & \vdots & \vdots & \ddots & \vdots \\
		\gamma(p-1) & \gamma(p-2) & \gamma(p-3) & \cdots & \gamma(0)
	\end{pmatrix} \begin{pmatrix}
		\beta_1 \\
		\beta_2 \\
		\beta_3 \\
		\vdots \\
		\beta_p
	\end{pmatrix} = \begin{pmatrix}
		\gamma(1) \\
		\gamma(2) \\
		\gamma(3) \\
		\vdots \\
		\gamma(p)
	\end{pmatrix}
$$

Falls die [[zettel/Autokovarianzfunktion (ACVF)|ACVF]] unbekannt ist, ist die [[zettel/Empirische Autokorrelation (emp. ACF)|emp. ACF]] zu nutzen

$$
	\begin{pmatrix}
		\hat{\gamma}(0) & \hat{\gamma}(1) & \hat{\gamma}(2) & \cdots & \hat{\gamma}(p-1) \\
		\hat{\gamma}(1) & \hat{\gamma}(0) & \hat{\gamma}(1) & \cdots & \hat{\gamma}(p-2) \\
		\hat{\gamma}(2) & \hat{\gamma}(1) & \hat{\gamma}(0) & \cdots & \hat{\gamma}(p-3) \\
		\vdots & \vdots & \vdots & \ddots & \vdots \\
		\hat{\gamma}(p-1) & \hat{\gamma}(p-2) & \hat{\gamma}(p-3) & \cdots & \hat{\gamma}(0)
	\end{pmatrix} \begin{pmatrix}
		\beta_1 \\
		\beta_2 \\
		\beta_3 \\
		\vdots \\
		\beta_p
	\end{pmatrix} = \begin{pmatrix}
		\hat{\gamma}(1) \\
		\hat{\gamma}(2) \\
		\hat{\gamma}(3) \\
		\vdots \\
		\hat{\gamma}(p)
	\end{pmatrix}
$$