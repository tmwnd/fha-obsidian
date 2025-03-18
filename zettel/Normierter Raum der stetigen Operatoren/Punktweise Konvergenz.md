Seien $((X, \oplus_X, \odot_X), \| \cdot \|_X)$, $((Y, \oplus_Y, \odot_Y), \| \cdot \|_Y)$ [[zettel/Normierter Raum|normierte Räume]], $(A_n)_{n \in \mathbb{N}} \in L(X, Y)$ eine Folge [[zettel/Normierter Raum/Operator/Stetigkeit|stetiger]] [[zettel/Metrischer Raum/Operator|Operatoren]].

$(A_n)_{n \in \mathbb{N}}$ heißt *punktweise konvergent* gegen $A \in L(X, Y)$, falls

$$
	\forall x \in X : \lim_{n \to \infty} \| A_nx - Ax \|_Y = 0
$$