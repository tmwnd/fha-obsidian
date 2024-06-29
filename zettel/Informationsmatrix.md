Sei $\Theta \subset \mathbb{R}^m$ [[zettel/Menge/Offenheit|offen]], $\vartheta \in \Theta$, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $x \in R$ $f(x, \vartheta)$ die [[zettel/μ-Dichte|μ-Dichte]] von $P_\vartheta^X$, $A = \{ x \in R, f(x, \vartheta) \gt 0 \}$ mit
- $A$ hängt nicht von $\vartheta = (\vartheta_1, \dots, \vartheta_m)^T$ ab
- $\forall x \in A : \vartheta \to f(x, \vartheta)$ partiell differenzierbar

und

$$
	\forall j \in \{ 1, \dots, m \}, \vartheta \in \Theta : \int \frac{\partial}{\partial\vartheta_j} f(x, \vartheta) d\mu = \frac{\partial}{\partial\vartheta_j} \int f(x, \vartheta) d\mu
$$

bzw.

$$
	\forall j \in \{ 1, \dots, m \}, \vartheta \in \Theta : E_\vartheta\left( \frac{\partial}{\partial\vartheta_j} \log(f(X, \vartheta)) \right) = 0
$$

und $\forall j, l \in \{ 1, \dots, m \}$ existiert

$$
	v_{j, l} = E_\vartheta\left( \frac{\partial}{\partial\vartheta_j} \log(f(X, \vartheta)) \frac{\partial}{\partial\vartheta_l} \log(f(X, \vartheta)) \right) \lt \infty
$$

Die *Informationsmatrix* $i_X(\vartheta)$ aus $X$ über $\vartheta$ ist definiert als
- $i_X(\vartheta) = [v_{j, l}]_{1 \le j \le m, 1 \le l \le m}$

und ist die [[zettel/Kovarianz|Kovarianzmatrix]] von

$$
	\left( \frac{\partial}{\partial\vartheta_1} \log(f(X, \vartheta)), \dots, \frac{\partial}{\partial\vartheta_m} \log(f(X, \vartheta)) \right)
$$