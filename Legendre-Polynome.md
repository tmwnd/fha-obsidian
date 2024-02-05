*Legendre-Polynome* sind im Interval $[-1, 1]$ orthogonal zueinander.

Es gilt

$$
	\forall L_i, L_j \in (L_n)_{n \in \mathbb{N}} : \langle L_i, L_j \rangle = \int_{-1}^1 L_i(x)L_j(x) dx = \frac{2}{2n + 1} \cdot \begin{cases}
		1, \quad \text{falls } i = j \\
		0, \quad \text{sonst}
	\end{cases}
$$

Z. B.
- $L_1(x) = x$
- $L_2(x) = \frac{1}{2}(3x^2-1)$
- $L_3(x) = \frac{1}{2}(5x^3-3x)$