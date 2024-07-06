Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathcal{L}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathcal{L}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $k$ eine [[zettel/Bedingte Verteilung|Bedingte Verteilung]] von $X$ unter $Y$, $f : (\mathbb{R}, \mathcal{L}^p) \to (\mathbb{R}, \mathcal{L})$ mit
- $\text{E}(|f(X)|) \lt \infty$

Es gilt
- $\int f(x) k(\cdot, dx) : (\mathbb{R}^d, \mathcal{L}^d) \to (\mathbb{R}, \mathcal{L})$

und für $P^Y$-fast alle $y \in \mathbb{R}^d$
- $\text{E}[f(X) \mid Y=y] = \int f(x) k(y, dx)$