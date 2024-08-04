Seien $X = (X_i)_{i \in \{ 1, \dots, n \}}$ unabhängige, gleichverteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit der Dichte

$$
	x \mapsto \frac{e^{a-x}}{(q + e^{a-x})^2} \mid x \in \mathbb{R}
$$

mit
- $a \in \mathbb{R}$ unbekannt

Es gilt

$$
	\log(f(x, a)) = \log\left( \prod_{i=1}^n \frac{e^{a-x_i}}{(1 + e^{a-x_i})^2} \right) = -\sum_{i=1}^n x_i + na - 2\sum_{i=1}^n \log(1 + e^{a-x_i})
$$

Um den Maximum-Likelihood-Schätzer zu erhalten, müssen wir folgendes Gleichungssystem lösen

$$
	\frac{\partial}{\partial a} \log(f(x, a)) = n - 2\sum_{i=1}^n \frac{e^{a-x_i}}{1 + e^{a-x_i}} \overset{!}{=} 0
$$