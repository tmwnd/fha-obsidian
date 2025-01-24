Sei $(V, \oplus, \odot)$ ein [[zettel/Reeller Vektorraum|Reeller Vektorraum]].

Eine Abbildung $\| \cdot \| : V \to \mathbb{R}_0^+$ heißt *Norm* in $(V, \oplus, \odot)$, falls
- $\forall v \in V : \| v \| \ge 0$ (Positivität I)
- $\forall v \in V : \| v \| = 0 \implies v = 0$ (Positivität II)
- $\forall v \in V, \lambda \in \mathbb{R} : \| \lambda \odot v \| = |\lambda| \| v \|$ (Homogenität)
- $\forall u, v \in V : \| u \oplus v \| \le \| u \| + \| v \|$ (Dreiecksungleichung)