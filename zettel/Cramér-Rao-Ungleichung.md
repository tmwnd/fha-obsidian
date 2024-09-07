Sei $d : (R, \mathscr{S}) \to (\mathbb{R}^m, \mathscr{B}^m) := (d_1, \dots, d_m)^T$ ein [[zettel/Schätzer|Schätzer]] für $\delta(\vartheta)$ mit
- $\forall i \in \{ 1, \dots, m \}, \vartheta \in \Theta : \text{E}_\vartheta((d_i(X)^2)) \lt \infty$
- $\forall i \in \{ 1, \dots, m \}, \vartheta \in \Theta : \vartheta \mapsto \text{E}_\vartheta(d_i(X))$ partiell differenzierbar

und

$$
	\forall i \in \{ 1, \dots, m \}, \vartheta \in \Theta : \frac{\partial}{\partial\vartheta_i} \text{E}_\vartheta[d_i(X)] = E_\vartheta\left[ d_i(X) \frac{\partial}{\partial\vartheta_i} \log(f(x, \vartheta)) \right]
$$

Es gilt

$$
	I_k := \Delta(\vartheta) = \left( \frac{\partial}{\partial\vartheta_j} \text{E}_{\vartheta_j}[d_i(X)] \right)_{j \in \{ 1, \dots, m \}, l \in \{ 1, \dots, k \}}
$$

und

$$
	\text{Cov}_\vartheta[d(X)] \ge \Delta(\vartheta)i_X(\vartheta)^{-1}\Delta(\vartheta)^T
$$