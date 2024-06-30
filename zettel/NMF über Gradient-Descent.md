Sei $V \in \mathbb{R}_+^{m \times n}$ [[zettel/Matrix/Dünnbesetztheit|Dünnbesetztheit]], $A \star B$ die komponentenweise Multiplikation der Matrizen $A$ und $B$.

Finde eine Lösung der [[zettel/Nonnegative-Matrix-Factorisation|NFM]] $V = EF$ über [[zettel/Gradient Descent|GD]]  mit
- der [[zettel/Loss-Funktion|Loss-Funktion]] $l(E, F)$ definiert als

$$
	l(E, F) = \| V - (E \star E)(F \star F) \|_\text{Fro}^2
$$