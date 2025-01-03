Sei $X$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $x$ eine Beobachtung von $X$, $\varphi(X)$ ein [[zettel/Statistischer Test|statistischer Test]], $T(X)$ eine Teststatistik.

Der $p$-Wert ist definiert als

$$
	p := \begin{cases}
		P_0(T(X) \ge T(x)) & \varphi(X) \text{ einseitig (rechtsstetig)} \\
		P_0(T(X) \le T(x)) & \varphi(X) \text{ einseitig (linksstetig)} \\
		2 \cdot \min(P_0(T(X) \le T(x)), P_0(T(X)) \ge T(x))) & \varphi(X) \text{ zweiseitig}
	\end{cases}
$$