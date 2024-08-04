Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \sim G(\alpha, \lambda)$ mit
- $(\alpha, \lambda) \in (0, \infty) \times (0, \infty)$ unbekannt
- $(X_i)_{i \in \{ 1, \dots, n \}}$ mit Wahrscheinlichkeit $1$ nicht alle gleich
- $\overline{X} := \frac{1}{n} \sum_{i = 1}^n X_i$
- $\overline{X^2} - \overline{X}^2 := \frac{1}{n} \sum_{i=1}^n X_i^2 - \left( \frac{1}{n} \sum_{i=1}^n X_i \right)^2 = \frac{1}{n} \sum_{i=1}^n (X_i - \overline{X})^2$

Es gilt
- $\overline{X^2} - \overline{X}^2 \gt 0$


Der [[zettel/Momentenschätzer|Momentenschätzer]] für $X$ ist definiert als

$$
	\text{Mo}_n := \left( \frac{\overline{X}^2}{\overline{X^2} - \overline{X}^2}, \frac{\overline{X}}{\overline{X^2} - \overline{X}^2} \right)
$$

da
- $\alpha = \frac{\text{E}_{\alpha, \lambda}[X_1]^2}{\text{Var}_{\alpha, \lambda}[X_1]}$
- $\lambda = \frac{\text{E}_{\alpha, \lambda}[X_1]}{\text{Var}_{\alpha, \lambda}[X_1]}$