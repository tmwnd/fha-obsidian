Sei $d : (R, \mathscr{S}) \to (\mathbb{R}^m, \mathcal{L}^m) := (d_1, \dots, d_m)^T$ mit
- $\forall i \in \{ 1, \dots, m \}, \vartheta \in \Theta : \text{E}_\vartheta((d_i(X)^2)) \lt \infty$
- $\forall i \in \{ 1, \dots, m \}, \vartheta \in \Theta : \vartheta \mapsto \text{E}_\vartheta(d_i(X))$ partiell differenzierbar

und

$$
	\forall i \in \{ 1, \dots, m \}, \vartheta \in \Theta : \frac{\partial}{\partial\vartheta_i} \text{E}_\vartheta[d_i(X)] = E_\vartheta\left[ d_i(X) \frac{\partial}{\partial\vartheta_i} \log(f(x, \vartheta)) \right]
$$

Es gilt

$$
	I_k = \Delta(\vartheta) = \left( \frac{\partial}{\partial\vartheta_i} \text{E}_{\vartheta_i}[d_i(X)] \right)_{j, l \in \{ 1, \dots, m \}}
$$

und

$$
	\text{Cov}_\vartheta[d(X)] \ge \Delta(\vartheta)i_X(\vartheta)^{-1}\Delta(\vartheta)^T
$$

Falls
- $d(X)$ [[zettel/Schätzer/Erwartungstreue|erwartungstreu]]
- $\delta(\vartheta) = \vartheta$
- $m = k = 1$

gilt

- $\Delta(\vartheta) = 1$

und

$$
	\text{Var}[d(X)] \ge \frac{1}{i_X(\vartheta)}
$$