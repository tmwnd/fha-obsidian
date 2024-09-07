Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\mathscr{B}$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]], $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathscr{B}})$ eine diskret verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $\delta_a$ das [[zettel/Dirac-Maß|Dirac-Maß]] und $(R, \mathscr{S})$ ein [[zettel/Messraum|Messraum]] mit
- $\forall x \in R : \{ x \} \in \mathscr{S}$
- $\exists S \in \mathscr{S} : P^X(S) = P(X \in S) = 1$

Es gilt

$$
	P^X = \sum_{s \in \S} P(X = s) \delta_R(a) = \sum_{a \in R} P(X = a)
$$