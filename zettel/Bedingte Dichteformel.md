Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathcal{L}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathcal{L}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $\mu$, $\nu$ [[zettel/Maß/σ-Endlichkeit|σ-endliche]] [[zettel/Maß|Maße]] auf $(\mathbb{R}^p, \mathcal{L}^p)$ bzw. $(\mathbb{R}^d, \mathcal{L}^d)$ mit
- $P^{(X, Y)} \ll \mu \otimes \nu$ mit $\mu \otimes \nu$-[[zettel/μ-Dichte|Dichte]] $f_{(X, Y)}$

Es gilt
- $P^Y \ll \nu$ mit $\nu$-[[zettel/μ-Dichte|Dichte]] $\forall y \in \mathbb{R}^d : f_Y(y) = \int f_{(X, Y)}(x, y) d\mu(x)$

und für $P^Y$-fast alle $y \in \mathbb{R}^d$
- $P^{X \mid Y=y} \ll \mu$

Die *bedingte Dichteformel* gilt für die zugehörige [[zettel/μ-Dichte|μ-Dichte]] und ist definiert als

$$
	\forall x \in \mathbb{R}^p : f_{X \mid Y=y}(x) = \frac{f_{(X, Y)}(x, y)}{f_Y(y)}
$$