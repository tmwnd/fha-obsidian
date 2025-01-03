Sei $X = (X^i)_{i \in \{ 1, \dots, d \}} : [0, \overline{T}] \to \mathbb{R}^d$ stetig mit stetiger [[zettel/Kovariation|Kovariation]], $F : \mathbb{R}^d \to \mathbb{R} \in C^2$ mit

Es gilt
$$
	[X^k, X^l]_t = \begin{cases}
		[X^k]_t & k=l \\
		\frac{1}{2} ([X^k + X^l]_t - [X^k]_t - [X^l]_t) & k \ne l
	\end{cases}
$$

und

$$
	F(X_t) = F(X_0) + \sum_{i=1}^d \int \frac{\partial}{\partial X_i} F(X_s) dX_s^i + \frac{1}{2} \sum_{i=1}^d \sum_{j=1}^d \int_0^t \frac{\partial}{\partial X_iX_j} F(X_s) d[X^i, X^j]_t
$$

Schreibe
- $\frac{\partial}{\partial X_i} F = F_{X_i}$
- $\frac{\partial^2}{\partial X_iX_j} = F_{X_i, X_j}$
- $dF(X_t) := \sum_{i=1}^d F_{X_i}(X_t) dX_j^i + \frac{1}{2} \sum_{i=1}^d \sum_{j=1}^d F_{X_i, X_j}(X_t) d[X^i, X^j]_t$