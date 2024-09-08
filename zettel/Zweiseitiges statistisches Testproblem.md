Sei $X$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $x$ eine Beobachtung von $X$, $T : (R,  \mathscr{S}) \to (\mathbb{R}, \mathscr{B})$ eine beliebige Teststatistik, $c_1, c_2 \in \mathbb{R}$ beliebige kritische Werte, $\gamma_1, \gamma_2 \in [0, 1]$ beliebige Randomisierungskonstanten mit
- $c_1 \le c_2$

Ein *zweiseitiges statistisches Testproblem* ist definiert über die [[zettel/Testfunktion|Testfunktion]]

$$
	\varphi(x) := I(T(x) \lt c_1) + \gamma_1I(T(x) = c_1) + I(T(x) \gt c_2) + \gamma_2I(T(x) = c_2)
$$