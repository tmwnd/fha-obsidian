Sei $X$ eine Menge.

Die [[zettel/Funktion|Funktion]] $d : X \times X \to \mathbb{R}_0^+$ heißt *Metrik* auf $x$, falls
- $\forall x, y \in X : d(x, y) \ge 0$ ([[zettel/Matrix/Indefinitheit|positive Semidefinitheit]])
- $\forall x, y \in X : d(x, y) = 0 \iff x = y$ (Einschränkung der [[zettel/Matrix/Indefinitheit|positiven Semidefinitheit]])
- $\forall x, y \in X : d(x, y) = d(y, x)$ (Symmetrie)
- $\forall x, y \in X : d(x, y) \le d(x, z) + d(z, y)$ (Dreiecksungleichung)