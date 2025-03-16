Sei $(X, \oplus, \odot)$ ein [[zettel/Linearer Raum|linearer Raum]].

Eine Abbildung $\| \cdot \| : X \to \mathbb{R}_0^+$ heißt *Norm* in $(X, \oplus, \odot)$, falls
- $\forall x \in X : \| x \| \ge 0$ (Positivität I)
- $\forall x \in X : \| x \| = 0 \iff x = 0$ (Positivität II)
- $\forall x \in X, \lambda \in \mathbb{R} : \| \lambda \odot x \| = |\lambda| \| x \|$ (Homogenität)
- $\forall x, y \in X : \| x \oplus y \| \le \| x \| + \| y \|$ (Dreiecksungleichung)