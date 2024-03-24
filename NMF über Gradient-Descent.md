Sei $V \in \mathbb{R}_+^{m \times n}$ [[sparse]], $A \star B$ die komponentenweise Multiplikation der Matrizen $A$ und $B$.

Finde eine Lösung der [[NMF, Nonnegative-Matrix-Factorisation|NFM]] $V = EF$ über [[Gradientenverfahren, Gradient Descent, GD|GD]]  mit
- der [[Loss-Funktion]] $l(E, F)$ definiert als

$$
	l(E, F) = \| V - (E \star E)(F \star F) \|_\text{Fro}^2
$$