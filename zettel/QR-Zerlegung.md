Sei $X \in \mathbb{R}^{m \times n}, y \in \mathbb{R}^m$, $w \in \mathbb{R}^n$ mit
- $m \ge n$

Das zu lösende Normalgleichungssystem ist
- $X^TXw = X^Ty$

Zerlege $X$, sodass
- $X = QR = Q\begin{pmatrix} \tilde{R} \\ 0 \end{pmatrix}$
- $Q \in \mathbb{R}^{m \times m}$
- $Q$ [[zettel/Matrix/Orthogonalität|orthogonal]]
- $R \in \mathbb{R}^{m \times n}$
- $\tilde{R} \in \mathbb{R}^{n \times n}$
- $\tilde{R}$ eine [[zettel/Matrix/Quadratische Matrix|quadratische]] [[zettel/Dreiecksmatrix|obere Dreiecksmatrix]]

Es gilt

$$
	X^TXw = \left( \tilde{R}^T, 0 \right)\underbrace{Q^TQ}_{I_m}\begin{pmatrix} \tilde{R} \\ 0 \end{pmatrix}w = \left( \tilde{R}^T, 0 \right)\begin{pmatrix} \tilde{R} \\ 0 \end{pmatrix}w = \tilde{R}^T\tilde{R}w = X^Ty
$$

---

Sei $X \in \mathbb{R}^{m \times n}$ $QR$-zerlegt, $w \in \mathbb{R}^n$ mit
- $l(w) = \frac{1}{2m} \| xw - y \|_2^2$ eine [[zettel/Loss-Funktion|Loss-Funktion]]

Es gilt

$$
	l(w) = \frac{1}{2m} \| xw - y \|_2^2 = \frac{1}{2m} \| QRw - y \|_2^2 = \frac{1}{2m} \| Q^T(QRw - y) \|_2^2 = \frac{1}{2m} \left\| \begin{pmatrix}
		\tilde{R} \\ 0
	\end{pmatrix}w - Q^Ty \right\|_2^2 = \frac{1}{2m} \left\| \begin{pmatrix}
		\tilde{R} \\ 0
	\end{pmatrix}w - \begin{pmatrix}
		c \\ d
	\end{pmatrix} \right\|_2^2 = \frac{1}{2m} (\| \tilde{R}w - c \|_2^2 + \| d \|_2^2)
$$

und
- $w^* = \arg\min_{w \in \mathbb{R}^n} l(w) \equiv \tilde{R}w = x$

---

Vorteile:
- Die [[zettel/Kondition|Kondition]] bleibt $\kappa(X)$

Nachteile:
- Die Komplexität der Zerlegung von $X$ ist $\mathcal{O}(n^3)$
- $X$ [[zettel/Matrix/Dünnbesetztheit|Dünnbesetztheit]], $Q$, $R$ nicht [[zettel/Matrix/Dünnbesetztheit|Dünnbesetztheit]]