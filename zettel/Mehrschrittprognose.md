Sei $(X_t)_{t \in \mathbb{Z}} \in \mathcal{L}^2(\Omega, \mathcal{A}, P)$ eine [[zettel/Zeitreihe|Zeitreihe]] mit $n \ge 2$ Beobachtungen, $h \gt 1$ und
- $\Theta_{n+h}$ das Ergebnis des [[zettel/Innovation-Algorithmus|Innovation-Algorithmus]] definiert als

$$
	\Theta_{n+1} := \begin{pmatrix}
		0 & 0 & 0 & \cdots & 0 \\
		\vartheta_{1, 1} & 0 & 0 & \cdots & 0 \\
		\vartheta_{2, 2} & \vartheta_{2, 1} & 0 & \cdots & 0 \\
		\vdots & \vdots & \vdots & \ddots & \vdots \\
		\vartheta_{n, n} & \vartheta_{n, n-1} & \vartheta_{n, n-2} & \cdots & 0
	\end{pmatrix}
$$

Die *Mehrschrittprognose* ist definiert als

$$
	P_n(X_{n+h}) = P_n(P_{n+h-1}(X_{n+h})) = P_n\left( \sum_{i=1}^{n+h-1} \vartheta_{n+h-1, i} \cdot (X_{n+h-i} - \hat{X}_{n+h-i}) \right) = \sum_{i=1}^{n+h-1} \vartheta_{n+h-1, i} \cdot P_n(X_{n+h-i} - \hat{X}_{n+h-i})
$$

bzw., da

$$
	\forall i \lt h : P_n(X_{n+h-i} - \hat{X}_{n+h-i}) = P_n(X_n+h-i) - P_n(P_{n+h-i-1} (X_{n+h-i})) = P_n(X_{n+h-i}) - P_n(X_{n+h-i}) = 0
$$

gilt

$$
	P_n(X_{n+h}) = P_n(P_{n+h-1}(X_{n+h})) = \sum_{i=h}^{n+h-1} \vartheta_{n+h-1, i} \cdot P_n(X_{n+h-i} - \hat{X}_{n+h-i})
$$