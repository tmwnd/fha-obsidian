Seien $(X, \| \cdot \|_X)$, $(Y, \| \cdot \|_Y)$ [[zettel/Normierter Raum|normierte Räume]].

Ein [[zettel/Linearer Raum/Operator/Linearität|linearer]] [[zettel/Metrischer Raum/Operator|Operator]] $A : X \to Y$ heißt *kompakt*, falls
- für alle [[zettel/Normierter Raum/Folgen/Beschränktheit|beschränkten]] Folgen $(x_n)_{n \in \mathbb{N}}$ eine in $Y$ [[zettel/Normierter Raum/Folgen/Konvergenz|konvergente]] Teilfolge $(Ax_{n_i})_{i \in \mathbb{N}}$ existiert

bzw.

$$
	\forall (x_n)_{n \in \mathbb{N}} \text{ beschränkt} \ \exists y \in Y, (n_i)_{i \in \mathbb{N}} \subseteq N : \lim_{i \to \infty} \| Ax_{n_i} - y \|_Y = 0
$$