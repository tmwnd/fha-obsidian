Seu $(X, \langle \cdot, \cdot \rangle)$ ein [[zettel/Hilbertraum|Hilbertraum]],$\| \cdot \| := x \mapsto \sqrt{\langle x, x \rangle}$.

Eine [[zettel/Funktion/Stetigkeit|stetige]] [[zettel/Linearer Raum/Bilinearform/Symmetrie|symmetrische]] [[zettel/Banachraum/Bilinearform|Bilinearform]] $a : X \times X \to \mathbb{R}$ heißt *elliptisch*, falls

$$
	\exists \lambda \in \mathbb{R} \ \forall x, y \in X : |a(x, y)| \le \lambda \| x \| \| y \|
$$

und

$$
	\exists \mu \in \mathbb{R}^+ \ \forall x \in X, x \ne 0 : a(x, x) \ge \mu \| x \|^2
$$