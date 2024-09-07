Sei $Y = m(X) + Z$ ein [[zettel/Nichtparametrisches Regressionsmodell|Nichtparametrisches Regressionsmodell]], $(X_n, Y_n)_{n \in \mathbb{N}} : (\Omega, \mathcal{A}) \to (\mathbb{R}^2, \mathscr{B}^2)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $K$ ein [[zettel/Kern|Kern]], $h \gt 0$ eine Bandbreite mit
- $K_h(\cdot) := \frac{1}{h}K\left( \frac{\cdot}{h} \right)$
- $\forall x, y \in \mathbb{R} : \hat{f}_{(X, Y)}(x, y) := \frac{1}{n} \sum_{i=1}^n K_h(x - X_i)K_h(y - Y_i)$
- $\forall x \in \mathbb{R} : \hat{f}_X(x) := \frac{1}{n} \sum_{i=1}^n K_h(x - X_i)$

Der *Nadaraya-Watson-Schätzer* ist definiert als

$$
	\forall x \in \mathbb{R} : \hat{m}(x) := \int_\mathbb{R} y \frac{\hat{f}_{(X, Y)}(x, y)}{\hat{f}_X(x)} dy = \frac{\sum_{i=1}^n K_h(x - X_i)Y_i}{\sum_{i=1}^n K_h(x - X_i)}
$$