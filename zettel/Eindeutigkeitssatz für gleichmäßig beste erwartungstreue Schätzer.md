Seien $d_1^*(X), d_2^*(X)$ gleichmäßig beste erwartungstreue [[zettel/Schätzer|Schätzer]] für $\delta(\vartheta)$.

Es gilt

$$
	\forall \vartheta \in \Theta : \text{E}_\vartheta\left[ (d_1^*(X) - d_2^*(X))^2 \right] = \text{Var}[d_1^*(X) - d_2^*(X)] = 2 \cdot  \text{Cov}_\vartheta[d_1^*(X), d_1^*(X) - d_2^*(X)] = 0
$$

und

$$
	\forall \vartheta \in \Theta : P_\vartheta(d_1^*(X) \ne d_2^*(X)) = 0
$$