Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $w \in \mathbb{R}^{m+1}$, $H(w)$ eine [[zettel/Hyperebene|Hyperebene]], $g(x, w)$ die Funktion aus $H(w)$.

Der optimale Parameter $\hat{w}$ wird über das [[zettel/nicht-restringiertes Optimierungsproblem|nicht-restringiertes Optimierungsproblem]] definiert als

$$
	\hat{w} = (\hat{v}, \hat{v}_0) = \min_{\hat{v} \ne 0, \hat{v}_0} \frac{1}{2} \| \hat{v} \|_2^2, \quad \forall i \in \{ 1, \dots, m \} : y_i(v^Tx_i + v_0) - 1 \ge 0
$$

TODO