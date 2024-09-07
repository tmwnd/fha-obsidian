Sei $d^* : (\mathbb{R}, \mathscr{S}) \to (\mathbb{R}, \mathscr{B})$ eine erwartungstreue [[zettel/Schätzfunktion|Schätzfunktion]] für $\delta(\vartheta)$ mit
- $\text{E}_\vartheta[d^*(X)^2] \lt \infty$

und

$$
	D := \{ d : (R, \mathscr{S}) \to (\mathbb{R}, \mathscr{B}) \mid \forall \vartheta \in \Theta : \text{E}_\vartheta[d(X)] = 0 \}
$$

$d^*(X)$ ist genau dann ein *gleichmäßig bester erwartungstreuer Schätzer*, falls

$$
	\forall \vartheta \in \Theta, \forall d \in D : \text{Cov}_\vartheta[d^*(X), d(X)] = 0
$$