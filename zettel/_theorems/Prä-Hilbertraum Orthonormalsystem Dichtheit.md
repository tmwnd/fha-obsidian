Sei $(X, \langle \cdot, \cdot \rangle)$ ein [[zettel/Prä-Hilbertraum|Prä-Hilbertraum]], $\| \cdot \| := x \mapsto \sqrt{\langle x, x \rangle}$, $(e_i)_{i \in \mathbb{N}}$ ein [[zettel/Prä-Hilbertraum/Orthonormalsystem|Orthonormalsystem]] in $(X, \langle \cdot, \cdot \rangle)$.

Folgende Aussagen sind äquivalent
- $\text{span}((e_i)_{i \in \mathbb{N}})$ ist [[zettel/Metrischer Raum/Teilmenge/Dichtheit|dicht]] in $X$
- es gilt

$$
	\forall x \in X : x = \sum_{i \in \mathbb{N}} \langle e_i, x \rangle e_i
$$

- es gilt

$$
	\forall x \in X : \| x \|^2 = \sum_{i \in \mathbb{N}} |\langle e_i, x \rangle|^2
$$