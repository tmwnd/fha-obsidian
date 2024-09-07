Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ unabhängige, gleichverteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma^2 > 0$ unbekannt

Es gilt

$$
	f(x, \mu, \sigma^2) = \left( \frac{1}{\sqrt{2\pi\sigma^2}} \right)^n \cdot e^{-\frac{1}{2\sigma^2} \sum_{i=1}^n (x_i - \mu)^2}
$$

Um den Maximum-Likelihood-Schätzer zu erhalten, müssen wir folgende Gleichungssysteme lösen

$$
	\frac{\partial}{\partial\mu} \log(f(x, \mu, \sigma^2)) = \frac{1}{\sigma^2} \sum_{i=1}^n (x_i - \mu) = 0
$$

und

$$
	\frac{\partial}{\partial\sigma^2} \log(f(x, \mu, \sigma^2)) = -\frac{n}{2\sigma^2} + \frac{1}{2\sigma^4} \sum_{i=1}^n (x_i - \mu)^2 = 0
$$

Der Maximum-Likelihood-Schätzer für $(\mu, \sigma^2)$ ist
- $(\hat{\mu}(X), \hat{\sigma}(X))$

mit
- $\hat{\mu}(X) = \frac{1}{n} \sum_{i=1}^n x_i$
- $\hat{\sigma}^2(X) =  \frac{1}{n} \sum_{i=1}^n (x_i - \hat{\mu}(X))^2$