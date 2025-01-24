Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{MA}(p)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]].

Die [[zettel/PACF|PACF]] $\rho : \mathbb{Z} \to [0, 1]$ für $(X_t)_{t \in \mathbb{Z}}$ ist gegeben durch

$$
	\forall h \in \mathbb{Z} : \tau(h) = \begin{cases}
		\phi_h & h \le p \\
		0 & h \gt p
	\end{cases}
$$