Seien $((X, \oplus_X, \odot_X), \| \cdot \|_X)$, $((Y, \oplus_Y, \odot_Y), \| \cdot \|_Y)$ [[zettel/Normierter Raum|normierte Räume]], $A : X \to Y$ ein [[zettel/Normierter Raum/Operator/Beschränktheit|beschränkter]] [[zettel/Metrischer Raum/Operator|Operator]], $\| A \|$ die [[zettel/Normierter Raum/Operatornorm|Operatornorm]].

Es gilt

$$
	\| A \| = \sup_{x \in X, \| x \|_X \le 1} \| Ax \|_Y
$$

und

$$
	\forall x \in X : \| Ax \|_Y \le \| A \| \| x \|_X
$$