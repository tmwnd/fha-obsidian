Sei $X$ eine Menge.

Die [[zettel/Funktion|Funktion]] $d : X \times X \to \mathbb{R}_0^+$ heißt *Metrik* auf $X$, falls
- $\forall x, y \in X : d(x, y) \ge 0$ (positive Semidefinitheit)
- $\forall x, y \in X : d(x, y) = 0 \iff x = y$ (Einschränkung der positiven Semidefinitheit)
- $\forall x, y \in X : d(x, y) = d(y, x)$ (Symmetrie)
- $\forall x, y, z \in X : d(x, y) \le d(x, z) + d(z, y)$ (Dreiecksungleichung)