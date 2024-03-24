Sei $x, \hat{w} \in \mathbb{R}^n$, $H(\hat{w})$ eine [[Hyperebene]], $g(x, \hat{w})$ die Funktion aus $H(w)$ mit

$$
	g(x, \hat{w}) = y_\hat{i} + \hat{v}^t(x - x_\hat{i}) = y_\hat{i} + \sum_{\hat{\alpha}_\hat{i} \gt 0} \hat{\alpha}_\hat{i}y_ix_i^T(x - x_\hat{i})
$$

Zum finden des optimalen Parameters $\hat{w}$ einer [[Trennende Hyperebene von überlappenden Clustern, Support-Vector Klassifikation, SVC|SVC]] gehen wir davon aus, dass sich die Daten-Paare $(x_i, y_i)_{i \in \{ 1, \dots, n \}}$ in der vorliegenden Dimension gut trennen lassen.

Falls dies nicht der Fall ist, lässt sich eventuell ein $m \gt n$ finden, sodass eine nichtlineare Transformation $\phi : \mathbb{R}^n \to \mathbb{R}^m$ die Daten in einen besser trennbaren Raum projiziert.

Anstatt $g(\Phi(x), \hat{w})$ zu berechnen, ersetzten wir jedes Skalarprodukt $\langle x_i, x_i \rangle$ durch einen *Kernel* $K(x_i, x_j)$ mit
- $K(x, x) \ge 0$
- $K(x, y) = K(y, x)$

Es gilt
- [[Trennende Hyperebene von überlappenden Clustern, Support-Vector Klassifikation, SVC|SVC]] mit *Kernel-Trick* erzeugt komplexere [[Hyperebene|Hyperebenen]]
- [[Trennende Hyperebene von überlappenden Clustern, Support-Vector Klassifikation, SVC|SVC]] mit *Kernel-Trick* kann die Daten potenziell besser trennen