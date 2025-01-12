Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $\lambda \in \mathbb{R}$ mit
- $\forall t \in \mathbb{Z} : X_t \gt 0$

Die *Box-Cox-Transformation* $T_\lambda : \mathcal{L}(\Omega, \mathcal{A}, P) \to \mathcal{L}(\Omega, \mathcal{A}, P)$ ist definiert als

$$
	\forall t \in \mathbb{Z} : T_\lambda(X_t) := \begin{cases}
		\frac{X_t^\lambda - 1}{\lambda} & \lambda \ne 0 \\
		\log(X_t) & \lambda = 0
	\end{cases}
$$