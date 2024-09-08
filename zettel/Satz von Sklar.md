Seien $X, Y$ reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $F_X$ stetig
- $F_Y$ stetig

Es existiert eine [[zettel/Copula|Copula]] $C_{(X, Y)} : [0, 1]^2 \to \mathbb{R}$ mit

$$
	\forall x, y \in \mathbb{R} : C_{(X, Y)}(F_X(x), F_Y(y)) := F_{(X, y)}(x, y) = P(X \le x, Y \le y)
$$

Es gilt
- $C_X \sim \mathfrak{R}(0, 1)$
- $C_Y \sim \mathfrak{R}(0, 1)$