Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]], $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine diskret verteilte [[Zufallsvariable]], $\delta_a$ das [[Dirac-Maß, Einpunktmaß|Dirac-Maß]] und $(R, \mathscr{S})$ ein [[Messraum]] mit
- $\forall x \in R : \{ x \} \in \mathscr{S}$
- $\exists S \in \mathscr{S} : P^X(S) = P(X \in S) = 1$

Es gilt

$$
	P^X = \sum_{s \in \S} P(X = s) \delta_R(a) = \sum_{a \in R} P(X = a)
$$