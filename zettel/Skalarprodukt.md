Sei $(V, \oplus, \odot)$ ein [[zettel/Reeller Vektorraum|reeller Vektorraum]].

Eine Abbildung $\langle \cdot, \cdot \rangle : V^2 \to \mathbb{R}$ heißt *Skalarprodukt* auf $(V, \oplus, \odot)$, falls
- $\forall u, v, w \in V : \langle u \oplus v, w \rangle = \langle u, w \rangle \oplus \langle v, w \rangle$ (Bilinearität I)
- $\forall u, v \in V, \lambda \in \mathbb{R} : \langle \lambda \odot u, v \rangle = \lambda \odot \langle u, v \rangle$ (Bilinearität II)
- $\forall u, v \in V : \langle u, v \rangle = \langle v, u \rangle$ (Symmetrie)
- $\forall v \in V : \langle v, v \rangle \ge 0$ (Positivität I)
- $\forall v \in V : \langle v, v \rangle = 0 \implies v = 0$ (Positivität II)