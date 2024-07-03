Sei $X : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $\mathcal{B}$ eine [[zettel/Unter-σ-Algebra|Unter-σ-Algebra]] von $\mathcal{A}$ mit
- $\text{E}\left[ X^2 \right] \lt \infty$

Es gilt
- $\text{E}\left[ \text{E}\left[ X \mid \mathcal{B} \right]^2 \right]$

und

$$
	\text{E}\left[ (X - \text{E}[X \mid \mathcal{B}])^2 \right] = \inf \left\{ \text{E}\left[ (X - Z)^2 \right] \mid Z : (\Omega, \mathcal{B}) \to (\mathbb{R}, \mathcal{L}), \text{E}\left[ Z^2 \right] \lt \infty \right\}
$$

und
- $L^2(\Omega, \mathcal{B}, P) \subseteq L^2(\Omega, \mathcal{A}, P)$
- $\text{E}[X \mid \mathcal{B}]$ ist die orthogonale Projektion von $X$ auf $L^2(\Omega, \mathcal{A}, P)$