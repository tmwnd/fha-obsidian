Seien $(Z_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(0, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $a, b, (y_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}$ beliebig, $X_i := a + by_i + Z_i$ mit
- $\sigma^2 \gt 0$ unbekannt
- $a, b$ unbekannt
- $(y_i)_{i \in \{ 1, \dots, n \}}$ bekannt
- $\exists i, j \in \{ 1, \dots, n \} : y_i \ne y_j$

Es gilt
- $\overline{y} = \frac{1}{n} \sum_{i=1}^n y_i$
- $\sigma_y^2 := \frac{1}{n} \sum_{i=1}^n (y_i - \overline{y})^2$
- $\alpha := a + b\overline{y}$
- $\beta := b\sigma_y$
- $(t_i)_{i \in \{ 1, \dots, n \}} := \left( \frac{y_i - \overline{y}}{\sigma_y} \right)_{i \in \{ 1, \dots, n \}}$

und

$$
	\forall i \in \{ 1, \dots, n \} : X_i = \alpha + \beta t_i + Z_i
$$