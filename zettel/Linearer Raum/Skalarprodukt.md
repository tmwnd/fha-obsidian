Sei $(X, \oplus, \odot)$ ein [[zettel/Linearer Raum|linearer Raum]] über $\mathbb{R}$.

Eine Abbildung $\langle \cdot, \cdot \rangle : X^2 \to \mathbb{R}$ heißt *Skalarprodukt* auf $(X, \oplus, \odot)$, falls
- $\forall x \in X : \langle x, x \rangle \ge 0$ (Positivität I)
- $\forall x \in X : \langle x, x \rangle = 0 \iff x = 0$ (Positivität II)
- $\forall x, y \in X : \langle x, y \rangle = \langle y, x \rangle$ (Symmetrie)
- $\forall x, y, z \in X : \langle x \oplus y, z \rangle = \langle x, z \rangle \oplus \langle y, z \rangle$ (Bilinearität I)
- $\forall x, y \in X, \lambda \in \mathbb{R} : \langle \lambda \odot x, y \rangle = \lambda \odot \langle x, y \rangle$ (Bilinearität II)