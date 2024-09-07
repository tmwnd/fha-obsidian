Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $k$ eine [[zettel/Bedingte Verteilung|Bedingte Verteilung]] von $X$ unter $Y$, $f : (\mathbb{R}, \mathscr{B}^p) \to (\mathbb{R}, \mathscr{B})$ mit
- $\text{E}(|f(X)|) \lt \infty$

Es gilt
- $\int f(x) k(\cdot, dx) : (\mathbb{R}^d, \mathscr{B}^d) \to (\mathbb{R}, \mathscr{B})$

und für $P^Y$-fast alle $y \in \mathbb{R}^d$
- $\text{E}[f(X) \mid Y=y] = \int f(x) k(y, dx)$