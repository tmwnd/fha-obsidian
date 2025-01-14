Sei $\alpha \gt 0$, $\lambda \gt 0$, $t \in (0, \infty)$ , die Gamma-[[zettel/Funktion|Funktion]] $\Gamma$ mit

$$
	\Gamma(z) = \int_0^\infty t^{z-1}e^{-t} dt
$$

und die $\lambda$-[[zettel/λ-Dichte|Dichte]] $g_{a, \lambda}$ definiert als 

$$
	g_{a, \lambda}(t) := \frac{\lambda^\alpha}{\Gamma(\alpha)}t^{\alpha-1}e^{-\lambda t}
$$

Sei $x \in \mathbb{R}$.

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] einer reelwertigen [[zettel/Zufallsvariable|Zufallsvariable]] $X$ heißt *gammaverteilt*, falls

$$
	F(x) = P(X \le x) = \begin{cases}
		0 & x \le 0 \\
		\int_0^x g_{a, \lambda}(t) dt & x \gt 0
	\end{cases}
$$

Schreibe
- $X \sim \mathfrak{G}(\alpha, \lambda)$