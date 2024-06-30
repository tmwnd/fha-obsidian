Sei $U \subseteq \mathbb{R}^n$, $a \in U$, $f : U \to \mathbb{R}^m$ eine [[zettel/Funktion|Funktion]] mit
- $f(\cdot)_m = f_m(\cdot)$

Die *Jacobi-Matrix* an der Stelle $a$ ist definiert als

$$
	J_f(a) := \left( \frac{\partial f_i}{\partial a_j} (a) \right)_{i \in \{ 1, \dots m \}, j \in \{ 1, \dots, n \}} = \pmatrix{
		\frac{\partial f_1}{\partial a_1} (a) & \cdots & \frac{\partial f_1}{\partial a_n} (a) \\
		\vdots & \ddots & \vdots \\
		\frac{\partial f_m}{\partial a_1} (a) & \cdots & \frac{\partial f_m}{\partial a_n} (a)
	}
$$