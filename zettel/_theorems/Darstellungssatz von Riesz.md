Sei $(X, \langle \cdot, \cdot \rangle_X)$ ein [[zettel/Hilbertraum|Hilbertraum]], $\| \cdot \|_X := x \mapsto \sqrt{\langle x, x \rangle_X}$, $l : X \to \mathbb{R}$ ein [[zettel/Linearer Raum/Operator/Linearität|lineares]] [[zettel/Normierter Raum/Operator/Stetigkeit|stetiges]] [[zettel/Funktional|Funktional]], $\| \cdot \|$ die [[zettel/Normierter Raum/Operatornorm|Operatornorm]].

Es gilt

$$
	\forall x, y \in X, \lambda, \mu \in \mathbb{R} : l(\alpha x + \beta y) = \alpha l(x) + \beta l(y)
$$

und

$$
	\forall x \in X : |l(x)| \le \| l \| \| x \|_X
$$

und

$$
	\exists! x \in X \ \forall y \in X : l(y) = \langle x, y \rangle_X \land \| x \|_X = \| l \|
$$