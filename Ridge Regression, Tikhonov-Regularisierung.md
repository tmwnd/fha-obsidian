Sei $X \in \mathbb{R}^{m \times n}$, $y \in \mathbb{R}^m$, $w \in \mathbb{R}^n$, $\alpha \gt 0$.

Minimiere

$$
	\| Xw - y \|_2^2 + \alpha \| w \|_2^2
$$

mit
- $\alpha \downarrow 0$ Gewichtung von kleinen [[Residuenvektor|Residuen]]
- $\alpha \uparrow \infty$ Gewichtung des Entgegenwirkens von [[Overfitting]]

Es gilt

$$
	\| Xw - y \|_2^2 + \alpha \| w \|_2^2 = \left\| \underbrace{\begin{pmatrix}
		X \\
		\sqrt{\alpha} I
	\end{pmatrix}}_\tilde{X}w - \underbrace{\begin{pmatrix}
		y \\
		0
	\end{pmatrix}}_\tilde{y} \right\|_2^2 = \| \tilde{X}w - \tilde{y} \|_2^2
$$

Das zu lösende Normalgleichungssystem ist
- $\tilde{X}^T\tilde{X}w = \tilde{X}^T\tilde{y}$ bzw.
- $(X^TX + \alpha I)w = X^Ty$

---

Sei $X \in \mathbb{R}^{m \times n}$, $y \in \mathbb{R}^m$, $w \in \mathbb{R}^n$ ein Löser von $X^TXw = X^Ty$, $\alpha \gt 0$.

Es gilt
- $\forall k \in \{ 1, \dots, m \} : w_k = 0 \iff |\langle x_k, r \rangle_2| = 0$ bzw.
- $r = Xw - y \perp x_k$