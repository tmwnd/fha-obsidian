Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]] mit $n$ Beobachtungen, $M_n = \text{span}(1, X_1, \dots, X_n) \subseteq \mathcal{L}^2(\Omega, \mathcal{A}, P)$, $a \in \mathbb{R}^n$ und
- $\gamma_n(h) : \mathbb{N} \times \mathbb{Z} \to \mathbb{R}^{n}$ definiert als

$$
	\forall h \in \mathbb{Z} : \gamma_n(h) := ((\gamma(i))_{i \in \{ h, \dots, h+n-1 \}})^T
$$

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

Das zu lösende LGS ist definiert als

$$
	\text{E}[X_{n+h} - P_{M_n}(X_{n+h})] = 0 \implies a_0 = \mu(1 - \sum_{i=1}^n a_i)
$$

und

$$
	\forall t \in \{ 1, \dots, n \} : \text{E}[( X_{n+h} - P_{M_n}(X_{n+h})) X_i] = 0 \iff \Gamma_n a = \gamma_n(h)
$$

Die *allgemeine Projektion* ist definiert als

$$
	\forall h \in \mathbb{N} : P_{M_n}(X_{n+h}) := a_0 + \sum_{i=1}^n a_i X_{n+1-i} = \mu + \sum_{i=1}^n a_i(X_{n+1-i} - \mu)
$$

Es gilt
- $\forall t, s \in \mathbb{Z} : P_{M_n}(\alpha X_t + \beta X_s) = \alpha P_{M_n}(X_t) + \beta P_{M_n}(X_s)$ (Linearität)