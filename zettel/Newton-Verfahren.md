Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $w^{(0)} \in \mathbb{R}^n$, $l$ eine zweifach differenzierbare [[zettel/Loss-Funktion|Loss-Funktion]] mit
- $l''$ [[zettel/Matrix/Regularität|regulär]]

Die $k$-te Iteration des *Newton Verfahrens* ist definiert als

$$
	w^{(k+1)} = \underbrace{w^{(k)} - l''\left( w^{(k)} \right)^{-1}l'\left( w^{(k)} \right)}_\text{linesares Gleichungssystem}
$$

Es gilt

$$
	l(w) \approx \underbrace{l(w^{(k)}) + l'(w^{(k)})(w - w^{(k)}) + \frac{1}{2}(w - w^{(k)})^Tl''(w^{(k)})(w - w^{(k)})}_\text{quadratisch}
$$