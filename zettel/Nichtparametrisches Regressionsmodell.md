Sei $(X, Y) : (\Omega, \mathcal{A}) \to (\mathbb{R}^2, \mathcal{L}^2)$ ein [[zettel/Zufallsvariable|Zufallsvektor]], $m : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$ eine Regressionsfunktion, $Z : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$ eine [[zettel/Zufallsvariable|zufällige]] Störung mit
- $X$, $Y$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]]
- $\forall n \in \mathbb{N} : (X_n, Y_n) \sim (X, Y)$
- $\text{E}[|m(X)|] \lt \infty$
- $\text{E}[|Z|] \lt \infty$
- $\text{E}[Z] = 0$
- $(X, Y)$ hat eine $\lambda \otimes \lambda$-[[zettel/μ-Dichte|Dichte]]

Das *nichtparametrische Regressionsmodell* ist definiert als

$$
	Y = m(X) + Z
$$

Es gilt $P$-f. s.
- $\text{E}[Y \mid X] = m(X)$

und für $P^X$-fast alle $x \in \mathbb{R}$ 
- $m(x) = \text{E}[Y \mid X=x] = \int_\mathbb{R} y f_{Y \mid X=x}(y) dy = \int_\mathbb{R} y \frac{f_{(X, Y)}(x, y)}{f_X(x)} dy$