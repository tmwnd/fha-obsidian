Sei $p \in \overline{\mathbb{N}}$.

Die Minkowski-Norm bzw. *$p$-Norm* auf $\mathbb{R}^n$ bzw. $\mathbb{C}^n$ ist definiert als

$$
	\forall x \in \mathbb{R}^n : \| x \|_p := \begin{cases}
		\left( \sum_{i=1}^n |x_i|^p \right)^\frac{1}{p} & p \ne \infty \\
		\max_{i \in \{ 1, \dots, n \}} |x_i| & p = \infty
	\end{cases}
$$

Die Minkowski-Norm bzw. *$p$-Norm* auf $C([a, b])$ ist definiert als

$$
	\forall f \in C([a, b]) : \| f \|_p := \begin{cases}
		\left( \int_a^b |f(x)|^p dx \right)^\frac{1}{p} & p \ne \infty \\
		\max_{x \in [a, b]} |f(x)| & p = \infty
	\end{cases}
$$