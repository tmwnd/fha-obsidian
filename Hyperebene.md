Sei $x, v \in \mathbb{R}^m \setminus \{ 0 \}$, $v_0 \in \mathbb{R}$ mit
- $w = (v, v_0)$
- $g(x, w) = v^Tx - v_0$

Eine *Hyperebene* $H$ ist definiert als

$$
	H(w) = \{ x \in \mathbb{R}^m \mid g(x, w) = 0 \}
$$

Es gilt
- $v \perp H(w)$

Falls $\| v \|_2 = 1$, gilt
- $v, v_0$ bis auf das Vorzeichen eindeutig festgelegt
- $|v_0| = d(H(w), 0)$
- $\text{sign}(g(x, w)) = \text{sign}(d(H(w), x))$
- $g(x, w) \gt 0$ $\implies$ $x$ liegt auf der Seite von $H$, in die $v$ zeigt
- $g(x, w) \lt 0$ $\implies$ $x$ liegt auf der Seite von $H$, in die $v$ nicht zeigt

---

Sei $w, \tilde{w} \in \mathbb{R}^{m+1}$, $\lambda \in \mathbb{R} \setminus \{ 0 \}$.

Es gilt

$$
	H(w) = H(\tilde{w}) \iff w = \lambda\tilde{w}
$$