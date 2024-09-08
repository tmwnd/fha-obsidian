Seien $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $\sigma_0^2, \sigma_1^2 \gt 0$ beliebig, $\text{H} : \sigma^2 = \sigma_0^2, \text{K} : \sigma^2 = \sigma_1^2$ ein [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]], $\alpha \in (0, 1)$ das vorgegebene Testniveau  mit
- $\mu \in \mathbb{R}$ bekannt
- $\sigma^2 \gt 0$ unbekannt
- $\sigma_0^2 \gt \sigma_1^2$

Die Dichte von $X$ ist definiert als

$$
	f_{\sigma^2}(x) := \left. \left( \frac{1}{\sqrt{2\pi\sigma^2}} \right)^n \exp\left( -\frac{1}{2\sigma^2} \sum_{i=1}^n (x_i - \mu)^2 \right) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

und

$$
	\frac{f_{\sigma_1^2}(x)}{f_{\sigma_0^2}(x)} = \left. \left( \frac{\sigma_1^2}{\sigma_0^2} \right)^{-\frac{n}{2}} \exp\left( -\left( \frac{1}{2\sigma_1^2} - \frac{1}{2\sigma_0^2} \right) \sum_{i=1}^n (x_i - \mu)^2 \right) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

Die *$\chi^2$-Teststatistik* $T$ ist definiert als

$$
	T(x) : \frac{1}{\sigma_0^2} \sum_{i=1}^n (x_i - \mu)^2 = \left. \sum_{i=1}^n \left( \frac{x_i - \mu}{\sigma_0} \right)^2 \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ der $\chi^2$-Teststatistik ist definiert als

$$
	\varphi(X) := \begin{cases}
		1, \quad & T(X) \gt c \\
		0, \quad & T(X) \le c
	\end{cases}
$$

mit
- $T(X) \sim \chi_n^2$
- $c := \chi_{n, 1-\alpha}^2$
- $\forall x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n : \frac{f_{\sigma_1^2}(x)}{f_{\sigma_0^2}(x)} \lesseqqgtr k \iff T(x) \lesseqqgtr c$

Es gilt
- die [[zettel/_examples/Gütefunktion Normalverteilung|Gütefunktion]] von $\varphi(X)$ ist streng monoton wachsend
- $\forall \mu \le a_0 : \text{E}_{\sigma^2}[\varphi(X)] \le \alpha$ $\implies$ $\varphi(X)$ ist der [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig beste]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ für das gegebene Testproblem

und

$$
	\text{E}_{\sigma^2}[\varphi(X)] = P_{\sigma^2}\left( \underbrace{\frac{\sigma_0^2}{\sigma^2} \cdot T(X)}_{\sim \chi_n^2} \ge \frac{\sigma_0^2}{\sigma^2} \cdot \chi_{n, 1-\alpha}^2 \right) = \frac{1}{2^{\frac{n}{2}} \Gamma(\frac{n}{2})} \int_{\frac{\sigma_0^2}{\sigma^2} \chi_{n, 1-\alpha}^2}^\infty X^{\frac{n}{2}-1} \exp\left( -\frac{X}{2} \right) dx
$$