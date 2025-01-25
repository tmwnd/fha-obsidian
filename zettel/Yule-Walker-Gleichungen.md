Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{AR}(p)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]], $(\psi_i)_{i \in \mathbb{N}} \in \mathbb{R}$ eine [[zettel/Folge/Absolute Konvergenz|absolut konvergent]] und
- $\Gamma_p, \hat{\Gamma}_p\in \mathbb{R}^{p \times p}$ definiert als

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

bzw.

$$
	\hat{\Gamma}_p := ((\hat{\gamma}(i-j))_{j \in \{ 1, \dots, p \}})_{i \in \{ 1, \dots, p \}} = \begin{pmatrix}
		\hat{\gamma}(1-1) & \hat{\gamma}(2-1) & \cdots & \hat{\gamma}(p-1) \\
		\hat{\gamma}(1-2) & \hat{\gamma}(2-2) & \cdots & \hat{\gamma}(p-2) \\
		\vdots & \vdots & \ddots & \vdots \\
		\hat{\gamma}(1-p) & \hat{\gamma}(2-p) & \cdots & \hat{\gamma}(p-p)
	\end{pmatrix} = \begin{pmatrix}
		\hat{\gamma}(0) & \hat{\gamma}(1) & \cdots & \hat{\gamma}(p-1) \\
		\hat{\gamma}(-1) & \hat{\gamma}(0) & \cdots & \hat{\gamma}(p-2) \\
		\vdots & \vdots & \ddots & \vdots \\
		\hat{\gamma}(1-p) & \hat{\gamma}(2-p) & \cdots & \hat{\gamma}(p-p)
	\end{pmatrix}
$$

mit
- $\forall t \in \mathbb{Z} : X_t = \varepsilon_t + \sum_{i \in \mathbb{N}} \psi_i B(\varepsilon_t)$

Die *Yule-Walker-Gleichungen* sind definiert als

$$
	\sigma^2 = \gamma(0) - \sum_{i=1}^p \phi_i \gamma(i) \quad \text{bzw.} \quad \hat{\sigma}^2 = \hat{\gamma}(0) - \sum_{i=1}^p \phi_i \hat{\gamma}(i)
$$

und

$$
	\Gamma_p (\phi_i)_{i \in \{ 1, \dots, p \}}^T = \gamma(p) \quad \text{bzw.} \quad \hat{\Gamma}_p (\phi_i)_{i \in \{ 1, \dots, p \}}^T = \hat{\gamma}(p)
$$