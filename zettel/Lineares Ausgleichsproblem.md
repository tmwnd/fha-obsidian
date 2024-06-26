Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $w \in \mathbb{R}^n$, $g$ eine [[zettel/Modellfunktion|Modellfunktion]] mit
- $g$ [[zettel/Funktion/Lineare Affinität|linear affin]]
- $l(w)$ die [[zettel/Loss-Funktion|Loss-Funktion]] des [[zettel/Least-Square Problem|Least-Square Problems]]

Es gilt bzgl. des [[zettel/Residuenvektor|Residuenvektors]]

$$
	L(w) = \begin{pmatrix}
		g(x_1, w) - y_1 \\
		\vdots \\
		g(x_m, w) - y_m
	\end{pmatrix} = \begin{pmatrix}
		G_{x_1}w + c_{x_i} - y_1 \\
		\vdots \\
		G_{x_m}w + c_{x_m} - y_m
	\end{pmatrix} = \underbrace{\begin{pmatrix}
		G_{x_1} \\
		\vdots \\
		G_{x_m}
	\end{pmatrix}}_A w - \underbrace{\begin{pmatrix}
		y_1 - c_{x_1} \\
		\vdots \\
		y_m - c_{x_m}
	\end{pmatrix}}_b = Aw - b
$$

und bzgl. der [[zettel/Loss-Funktion|Loss-Funktion]]

$$
	\begin{aligned}
	l(w) & = \frac{1}{2m} \| Aw - b \|_2^2 \\
	l'(w) & = \frac{1}{m} A^T (Aw - b) \\
	l''(w) & = \frac{1}{m} A^TA
	\end{aligned}
$$

und
- $l$ [[zettel/Funktion/Konvexität|konvex]] $\implies$ jedes lokale Minimum ist ein globales Minimum
- $l'(w) = 0 \iff A^TAw = A^Tb$
- $l''(w)$ [[zettel/Matrix/Indefinitheit|positiv semidefinit]] $\implies$ $w$ ist ein lokales Minimum

Das zu lösende Normalgleichungssystem ist
- $\underbrace{w^* = \arg\min_{w \in \mathbb{R}^n} l(w)}_\text{numerisches Optimierungsproblem} \equiv \underbrace{A^TAw = A^Tb}_\text{linesares Gleichungssystem}$^[$w$ nicht eindeutig, da $g$ mehrere globale Minima enthalten kann]