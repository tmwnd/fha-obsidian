Sei $(X_t)_{t \in \mathbb{N}} \sim \text{MA}(1)$.

Die [[zettel/Autokovarianzfunktion (ACVF)|ACVF]] ist gegeben durch

$$
	\forall t, h \in \mathbb{Z} : \gamma(t+h, t) = \begin{cases}
		\sigma^2 \cdot (1 + \alpha^2) & h = 0 \\
		\sigma^2 \cdot \alpha & h \in \{ -1, 1 \} \\
		0 & \text{sonst}
	\end{cases}
$$