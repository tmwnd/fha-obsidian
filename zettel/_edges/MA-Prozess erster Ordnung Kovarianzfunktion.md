Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(1)$.

Die [[zettel/Kovarianzfunktion|Kovarianzfunktion]] $\gamma : \mathbb{Z}^2 \to \mathbb{R}$ für $(X_t)_{t \in \mathbb{Z}}$ ist gegeben durch

$$
	\forall t, h \in \mathbb{Z} : \gamma(t+h, t) = \begin{cases}
		\sigma^2 \cdot (1 + \vartheta^2) & h = 0 \\
		\sigma^2 \cdot \vartheta & h \in \{ -1, 1 \} \\
		0 & \text{sonst}
	\end{cases}
$$