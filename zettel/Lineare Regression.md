Seien $(x_i, y_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^2$ unabhängige und identisch verteilte Daten.

*Lineare Regression* definiert eine Funktion $f : \mathbb{R} \to \mathbb{R}$ über den minimalen $L^2$-Abstand

$$
	\underset{\alpha, \beta \in \mathbb{R}}{\arg\min} \frac{1}{n} \sum_{i=1}^n (y_i - f(x_i))^2 = \underset{\alpha, \beta \in \mathbb{R}}{\arg\min} \frac{1}{n} \sum_{i=1}^n (y_i - (\alpha x_i + \beta))^2
$$

als

$$
	\forall x \in \mathbb{R} : f(x) = \alpha x + \beta
$$

sodass
- $\forall i \in \{ 1, \dots, n \} : y_i \approx \hat{y}_i := f(x_i)$