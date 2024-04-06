Sei $X$ eine Menge.

Die [[Funktion]] $d : X \times X \to \mathbb{R}_0^+$ heißt *Metrik* auf $x$, falls
- $\forall x, y \in X : d(x, y) \ge 0$ ([[Matrix definit|positive Semidefinitheit]])
- $\forall x, y \in X : d(x, y) = 0 \iff x = y$ (Einschränkung der [[Matrix definit|positiven Semidefinitheit]])
- $\forall x, y \in X : d(x, y) = d(y, x)$ (Symmetrie)
- $\forall x, y \in X : d(x, y) \le d(x, z) + d(z, y)$ (Dreiecksungleichung)