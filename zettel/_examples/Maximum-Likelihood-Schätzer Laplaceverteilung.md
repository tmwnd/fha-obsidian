Seien $X = (X_i)_{i \in \{ 1, \dots, n \}}$ unabhängige, gleichverteilte reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit der Dichte

$$
	x \mapsto \frac{1}{2\sigma} e^{-\frac{|x - \mu|}{\sigma}} \mid x \in \mathbb{R}
$$

mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma \gt 0$ unbekannt

Es gilt

$$
	\log(f(x, \mu, \sigma)) = \log\left( \prod_{i=1}^n \frac{1}{2\sigma} e^{-\frac{|x_i - \mu|}{\sigma}} \right) = -n\log(2) - n\log(\sigma) - \frac{1}{\sigma}\sum_{i=1}^n |x_i - \mu|
$$

Um den Maximum-Likelihood-Schätzer zu erhalten, müssen wir folgende Gleichungssysteme lösen

$$
	\sum_{i=1}^n |x_i - \mu| \to \min
$$

und

$$
	\frac{\partial}{\partial\sigma} \log(f(x, \mu, \sigma)) = -\frac{n}{\sigma} + \frac{1}{\sigma^2} \sum_{i=1}^n |x_i - \mu| \overset{!}{=} 0
$$

Der Maximum-Likelihood-Schätzer für $(\mu, \sigma)$ ist
- $(\hat{\mu}(X), \hat{\sigma}(X))$

mit
- $\hat{\mu}(X) \in [X_{\lceil \frac{n}{2} \rceil}, X_{\lfloor \frac{n}{2}+1 \rfloor}]$
- $\hat{\sigma}(X) = \frac{1}{n} \sum_{i=1}^n |x_i - \hat{\mu}(X)|$