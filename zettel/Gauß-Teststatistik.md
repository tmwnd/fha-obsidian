Sei $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $\mu_0, \mu_1 \in \mathbb{R}$ beliebig, $\text{H} : \mu = \mu_0, \text{K} : \mu = \mu_1$ ein [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]], $k \in (0, \infty)$, $\alpha \in (0, 1)$ das vorgegebene Testniveau mit
- $\mu$ unbekannt
- $\sigma^2$ bekannt
- $\mu_1 \gt \mu_0$

Die Dichte von $X$ ist definiert als

$$
	f_\mu(x) := \left. \left( \frac{1}{\sqrt{2\pi\sigma^2}} \right)^n \exp\left( -\frac{1}{2\sigma^2} \sum_{i=1}^n (x_i - \mu)^2 \right) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

und

$$
	\frac{f_{\mu_1}(x)}{f_{\mu_0}(x)} = \left. \exp\left( \frac{1}{\sigma^2} \sum_{i=1}^n x_i(\mu_1 - \mu_0) - n\frac{\mu_1^2 - \mu_0^2}{2\sigma^2} \right) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

Die *Gauß-Teststatistik* $T$ ist definiert als

$$
	T(x) := \left. \frac{1}{\sqrt{n\sigma^2}} \sum_{i=1}^n (x_i - \mu_0) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ der Gauß-Teststatistik ist definiert als

$$
	\varphi(X) := \begin{cases}
		1 \quad & T(X) \gt c \\
		0 \quad & T(X) \le c
	\end{cases}
$$

mit
- $T(X) \sim \mathcal{N}\left( \sqrt{n}\frac{\mu - \mu_0}{\sqrt{\sigma^2}}, 1 \right)$, falls $\text{H}$ gültig ist
- $c := \phi^{-1}(1-\alpha)$
- $\forall x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n : \frac{f_{\mu_1}(x)}{f_{\mu_0}(x)} \lesseqqgtr k \iff T(x) \lesseqqgtr c$

Es gilt
- die [[zettel/_examples/Gütefunktion Normalverteilung|Gütefunktion]] von $\varphi(X)$ ist streng monoton wachsend
- $\forall \mu \le a_0 : \text{E}_\mu[\varphi(X)] \le \alpha$ $\implies$ $\varphi(X)$ ist der [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig beste]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ für das gegebene Testproblem