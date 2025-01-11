Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]] mit $n$ Beobachtungen, $\gamma_n := ((\gamma(t))_{t \in \{ 1, \dots, n \}})^T$ und
- $\Gamma_n \in \mathbb{R}^{n \times n}$ definiert als

$$
	\Gamma_p := ((\gamma(i-j))_{j \in \{ 1, \dots, p \}})_{i \in \{ 1, \dots, p \}} = \begin{pmatrix}
		\gamma(1-1) & \gamma(2-1) & \cdots & \gamma(p-1) \\
		\gamma(1-2) & \gamma(2-2) & \cdots & \gamma(p-2) \\
		\vdots & \vdots & \ddots & \vdots \\
		\gamma(1-p) & \gamma(2-p) & \cdots & \gamma(p-p)
	\end{pmatrix} = \begin{pmatrix}
		\gamma(0) & \gamma(1) & \cdots & \gamma(p-1) \\
		\gamma(-1) & \gamma(0) & \cdots & \gamma(p-2) \\
		\vdots & \vdots & \ddots & \vdots \\
		\gamma(1-p) & \gamma(2-p) & \cdots & \gamma(p-p)
	\end{pmatrix}
$$

- $\phi_n := \Gamma_n^{-1} \gamma_n$
- $v_n := \text{E}[(X_{n+1} - P_{M_n}(X_{n+1}))^2]$

mit
- $\forall t \in \mathbb{Z} : \mu_t = 0$

Der *Durbin-Levinson-Algorithmus* definiert folgende Rekursionsvorschriften

$$
	\phi_{n+1, n+1} = \left( \gamma(n+1) - \sum_{i=1}^n \phi_{n, i} \gamma(n+1-i) \right) v_n^{-1}
$$

und

$$
	\begin{pmatrix}
		\phi_{n+1, 1} \\
		\phi_{n+1, 2} \\
		\vdots \\
		\phi_{n+1, n}
	\end{pmatrix} = \begin{pmatrix}
		\phi_{n, 1} \\
		\phi_{n, 2} \\
		\vdots \\
		\phi_{n, n}
	\end{pmatrix} - \phi_{n+1, n+1} \cdot \begin{pmatrix}
		\phi_{n, n} \\
		\phi_{n, n-1} \\
		\vdots \\
		\phi_{n, 1}
	\end{pmatrix}
$$

und

$$
	v_{n+1} = v_n(1 - \phi_{n+1, n+1}^2)
$$

und

$$
	\hat{X}_{t+1} := P_{n+1}(X_{n+1}) = \sum_{i=1}^{n+1} \phi_{n+1, i} X_{n+1-i}
$$

mit
- $\phi_{1, 1} := \rho(1)$
- $v_0 = \gamma(0)$