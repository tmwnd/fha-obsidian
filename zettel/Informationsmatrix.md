Sei $\Theta \subset \mathbb{R}^k$ [[zettel/Menge/Offenheit|offen]], $\vartheta \in \Theta$, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $x \in R$ $f(x, \vartheta)$ die [[zettel/μ-Dichte|μ-Dichte]] von $P_\vartheta^X$, $A := \{ x \in R \mid f(x, \vartheta) \gt 0 \}$ mit
- $A$ hängt nicht von $\vartheta = (\vartheta_1, \dots, \vartheta_k)^T$ ab
- $\forall x \in A : \vartheta \mapsto f(x, \vartheta)$ partiell differenzierbar

und

$$
	\forall j \in \{ 1, \dots, m \}, \vartheta \in \Theta : \int \frac{\partial}{\partial\vartheta_j} f(x, \vartheta) d\mu = \frac{\partial}{\partial\vartheta_j} \int f(x, \vartheta) d\mu
$$

bzw.

$$
	\forall j \in \{ 1, \dots, m \}, \vartheta \in \Theta : \text{E}_\vartheta\left[ \frac{\partial}{\partial\vartheta_j} \log(f(X, \vartheta)) \right] = 0
$$

und $\forall j, l \in \{ 1, \dots, k \}$ existiert

$$
	v_{j, l} := \text{E}_\vartheta\left[ \frac{\partial}{\partial\vartheta_j} \log(f(X, \vartheta)) \frac{\partial}{\partial\vartheta_l} \log(f(X, \vartheta)) \right] \lt \infty
$$

Die *Informationsmatrix* $i_X(\vartheta)$ aus $X$ über $\vartheta$ ist definiert als
- $i_X(\vartheta) := [v_{j, l}]_{j, l \in \{ 1, \dots, k \}}$

und ist die [[zettel/Kovarianz|Kovarianzmatrix]] von

$$
	\left( \frac{\partial}{\partial\vartheta_j} \log(f(X, \vartheta)) \right)_{j \in \{ 1, \dots, l \}}
$$