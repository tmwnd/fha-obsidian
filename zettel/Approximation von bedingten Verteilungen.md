Seien $X$, $Y$ reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $n \in \mathbb{N}$, $(X_i, Y_i)_{i \in \{ 1, \dots, n \}}$ unabhängige Kopien von $X$, $Y$, $C_{(X, Y)} : [0, 1]^2 \to \mathbb{R}$ eine [[zettel/Copula|Copula]], $t \in \mathbb{R}$ mit
- $\forall x, y \in \mathbb{R} : \lim_{\epsilon \to 0^+} P(X \le x \mid Y \in [y, y+\epsilon]) = \partial_y C_{(X, Y)}(F_X(x), F_Y(y))$

Es gilt
- $\forall x, y \in \mathbb{R} : \text{E}[\partial_y C_{(X, Y)}(F_X(x), F_Y(y)) I(Y \le t)] = P(X \le x, Y \le t)$

und

$$
	P(X \in B \mid Y = y) \approx \frac{\frac{1}{n} \sum_{i=1}^n I(X_i \in B, Y_i \in (y-\epsilon, y+\epsilon))}{\frac{1}{n} \sum_{i=1}^n I(Y_i \in (y-\epsilon, y+\epsilon))}
$$