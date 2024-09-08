Sei $X$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $x$ eine Beobachtung von $X$, $T : (R,  \mathscr{S}) \to (\mathbb{R}, \mathscr{B})$ eine beliebige Teststatistik, $c \in \mathbb{R}$ ein beliebiger kritischer Wert, $\gamma \in [0, 1]$ eine beliebige Randomisierungskonstante.

Ein *einseitiges statistisches Testproblem* ist definiert über die [[zettel/Testfunktion|Testfunktion]]

$$
	\varphi(x) := \underbrace{I(T(x) \gt c)}_\text{Ablehnungsbereich} + \underbrace{\gamma I(T(x) = c)}_\text{Randomisierungsbereich}
$$