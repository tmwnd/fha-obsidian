Sei $X$ ein [[zettel/Linearer Raum|linearer Raum]] definiert als

$$
	X := \left\{ f \mid f \in C^1([a, b]) \ \left| \ f(a) = f(b) = 0 \land \int_a^b f^2(x) dx + \int_a^b f'^2(x) dx \lt \infty \right.\right\}
$$

und $\langle \cdot, \cdot \rangle$ ein [[zettel/Linearer Raum/Skalarprodukt|Skalarprodukt]] definiert über

$$
	\forall f, g \in X : \langle f, g \rangle := \int_a^b f(x)g(x) dx + \int_a^b f'(x)g'(x) dx
$$

mit zugehöriger [[zettel/Linearer Raum/Norm|Norm]] $\| \cdot \|$ mit

$$
	\forall f \in X : \| f \| = \sqrt{\langle f, f \rangle } = \sqrt{\| f \|_2^2 + \| f' \|_2^2}
$$

Die [[zettel/Metrischer Raum/Vervollständigung|Vervollständigung]] von $(X, \langle \cdot, \cdot \rangle)$ heißt *Sobolevraum* $(H_0^1([a, b]), \langle \cdot, \cdot \rangle_{(H_0^1([a, b])} := (f, g) \mapsto \langle f, g \rangle_{L^2([a, b])} + \langle f', g' \rangle_{L^2([a, b])})$

Es gilt
- $X$ ist nicht [[zettel/Metrischer Raum/Vollständigkeit|vollständig]]
- $(H_0^1([a, b]), \langle \cdot, \cdot \rangle_{(H_0^1([a, b])}$ ist ein [[zettel/Linearer Raum/Hilbertraum|Hilbertraum]]