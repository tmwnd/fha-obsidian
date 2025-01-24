Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Zeitreihe|Zeitreihe]] mit $n \ge 2$ Beobachtungen und
- $\forall t \in \{ 1, \dots, n \} : \beta_t \in \mathbb{R}^{t-1}$
- $\forall t \in \{ 1, \dots, n \} : \hat{X}_t := \sum_{i=1}^t \beta_{t, i} X_i$
- $\forall t \in \{ 1, \dots, n \} : U_t := X_t - \hat{X}_t$ der ein-Schritt-Prognosefehler bzw. die Innovation

mit
- $\forall t \in \mathbb{Z} : \mu_t = 0$

Der *Innovation-Algorithmus* definiert folgende Rekursionsvorschriften

$$
	\Theta_{n+1} := \begin{pmatrix}
		0 & 0 & 0 & \cdots & 0 \\
		\vartheta_{1, 1} & 0 & 0 & \cdots & 0 \\
		\vartheta_{2, 2} & \vartheta_{2, 1} & 0 & \cdots & 0 \\
		\vdots & \vdots & \vdots & \ddots & \vdots \\
		\vartheta_{n, n} & \vartheta_{n, n-1} & \vartheta_{n, n-2} & \cdots & 0
	\end{pmatrix} := \begin{pmatrix}
		1 & 0 & 0 & \cdots & 0 \\
		-\beta_{2, 1} & 1 & 0 & \cdots & 0 \\
		-\beta_{3, 1} & -\beta_{3, 2} & 1 & \cdots & 0 \\
		\vdots & \vdots & \vdots & \ddots & \vdots \\
		-\beta_{n-1, 1} & -\beta{n-1, 2} & \beta_{n-2, 3} & \cdots & 1
	\end{pmatrix}^{-1} - I_{n+1}
$$

mit

$$
	\forall k \in \mathbb{N}_0, k \lt n : \vartheta_{n+1, n+1-k} := v_k^{-1} \left( \gamma(n+2, k+1) - \sum_{i=0}^{k-1} \vartheta_{k, k-1} \cdot \vartheta_{n+1, n+1-i} \cdot v_i \right)
$$

und

$$
	v_{n+1} := \gamma(n+2, n+2) - \sum_{i=0}^n \vartheta_{n+1, n+1-i}^2 \cdot v_i
$$

und

$$
	\hat{X}_{n+1} := \sum_{i=1}^n \vartheta_{n, i} (X_{n+1-i} - \hat{X}_{n+1-i})
$$

mit
- $\hat{X}_0 = 0$
- $v_0 := \gamma(1, 1)$