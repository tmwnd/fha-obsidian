Sei $d^* : (\mathbb{R}, \mathscr{S}) \to (\mathbb{R}, \mathscr{B})$ eine erwartungstreue [[zettel/Schätzfunktion|Schätzfunktion]] für $\delta(\vartheta)$ mit
- $\text{E}_\vartheta[d^*(X)^2] \lt \infty$
- $\delta : \Theta \to \mathbb{R}$ partiell differenzierbar
- $m = 1$

$d^*$ heißt *gleichmäßig beste erwartungstreue Schätzfunktion*, falls

$$
	\forall d : (R, \mathscr{S}) \to (\mathbb{R}, \mathscr{B}), \text{E}_\vartheta[d(X)^2] \lt \infty : \text{Var}_\vartheta[d^*(X)] \le \text{Var}_\vartheta[d(X)]
$$

Es gilt

$$
	\text{Var}_\vartheta[d^*(X)] = \left( \frac{\partial}{\partial\vartheta_j} \delta(\vartheta) \right)_{j \in \{ 1, \dots, k \}}i_X(\vartheta)^{-1}\left( \frac{\partial}{\partial\vartheta_j} \delta(\vartheta) \right)_{j \in \{ 1, \dots, k \}}^T
$$