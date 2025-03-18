Sei $((X, \oplus_X, \odot_X), \| \cdot \|_X)$ ein [[zettel/Banachraum|Banachraum]], $A : X \to X$ ein [[zettel/Linearer Raum/Operator/Linearität|linearer]] [[zettel/Normierter Raum/Operator/Beschränktheit|beschränkter]] [[zettel/Metrischer Raum/Operator|Operator]] in $X$, $\| \cdot \|$ die [[zettel/Normierter Raum/Operatornorm|Operatornorm]] mit
- $\| A \| \lt 1$

Es gilt

$$
	\forall b \in X \ \exists x \in X : (I - A)x = b
$$

und

$$
	\exists c \in \mathbb{R}^+ \forall x, b \in X, (I - A)x = b = \| x \|_X \le c \| b \|_x
$$

und

$$
	(I - A)^{-1} = \sum_{k=1}^\infty A^k
$$

und

$$
	\| (I - A)^{-1} \| \le \frac{1}{1 - \| A \|}
$$

Sei $b \in X$, $(x_n)_{n \in \mathbb{N}} \in X$ eine Folge definiert als

$$
	\forall n \in \mathbb{N} : x_n := Ax_{n-1} + b
$$

Es gilt

$$
	\forall x_0 \in X : \lim_{n \to \infty} (I - A)x_n = b
$$