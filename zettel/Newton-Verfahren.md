Sei $f : \mathbb{R} \to \mathbb{R}$ eine Funktion, $x, y \in \mathbb{R}$ und
- $(x_i)_{i \in \mathbb{N}_0}$ ein Schätzer von $x$ definiert als

$$
	\forall i \in \mathbb{N}_0 : x_{i+1} := x_i - \frac{f(x_i)}{f'(x_i)}
$$

mit
- $f(x) - y = 0$
- $x_0 \in \mathbb{R}$

Es gilt (hoffentlich)

$$
	\lim_{n \to \infty} f(x_i) - y = 0
$$