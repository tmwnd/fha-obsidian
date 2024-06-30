Sei $w \in \mathbb{R}^n$, $f(w)$ eine nicht-differenzierbare Funktion.

Der [[zettel/Subgradient|Subgradient]] von $f$ wird iterativ über alle $k$-Komponenten von $w$ bestimmt.

Minimiere

$$
	w_k^* = \underset{w \in \mathbb{R}^n}{\arg\min} f(w) = \partial_{w_k} f(w)
$$