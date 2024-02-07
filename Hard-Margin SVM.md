Eine *Hard-Margin SVM* ist ein [[Perzeptron]] mit maximalem Rand.

Sei $X, y$ ein [[Datensatz]], $N = |X|$ mit
- $w$ dem Gewichtsvektor
- $g$ die finale [[Hypothese]]

Minimiere

$$
	\frac{1}{2}w^Tw
$$

mit den Nebenbedingungen

$$
	\forall n \in \{ 1, \dots, N \} : y_n(w^Tx_n + b) \ge 1
$$

Es gilt

$$
	g(x) = \text{sign}\left( \sum_{n=1}^N \alpha_ny_nx_n^Tx + b \right)
$$

mit dem Lösungsvektor $\alpha$.

und
- $\alpha$ ist sparse besetzt
- Die *Stützwerte* sind definiert als $\forall k \in \{ 1, \dots, N \} : \alpha_k \ne 0$
- Die *Stützvektoren* sind definiert als $\{ x_k \mid \alpha_k \ne 0, k \in \{ 1, \dots, N \} \}$