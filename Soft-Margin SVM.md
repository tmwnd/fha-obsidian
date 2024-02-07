Eine *Soft-Margin SVM* ist eine [[Hard-Margin SVM]], bei der jedoch der Rand verletzt werden darf.

Sei $X, y$ ein [[Datensatz]], $N = |X|$ mit
- $w$ dem Gewichtsvektor
- $\forall n \in \{ 1, \dots, N \} : \xi_n = \max(0, 1 - y_n(w^Tw_n + b))$

Minimiere

$$
	\frac{1}{2}w^Tw + C\sum_{n=1}^N \xi_n \
$$

mit den Nebenbedingungen

$$
	\forall n \in \{ 1, \dots, N \} : y_n(w^Tx_n + b) \ge 1 - \xi_n
$$

Es gilt

$$
	g(x) = \text{sign}\left( \sum_{n=1}^N \alpha_ny_nx_n^Tx + b \right)
$$