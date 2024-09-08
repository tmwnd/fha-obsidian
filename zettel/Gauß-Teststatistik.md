Sei $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(a, \sigma^2) \mid n \in \mathbb{N}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $a_0, a_1 \in \mathbb{R}$ beliebig, $\text{H} : a = a_0, \text{K} : a = a_1$ ein [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]], $k \in (0, \infty)$, $\alpha \in (0, 1)$ das vorgegebene Testniveau mit
- $a_1 \gt a_0$
- $\sigma^2$ unbekannt

und

$$
	\frac{f_{a_1}(x)}{f_{a_0}(x)} = \exp\left( \frac{1}{\sigma^2} \sum_{i=1}^n x_i(a_1 - a_0) - n\frac{a_1^2 - a_0^2}{2\sigma^2} \right)
$$

Die *Gauß-Teststatistik* ist definiert als

$$
	T(x) := \left. \frac{1}{\sqrt{n\sigma^2}} \sum_{i=1}^n (x_i - a_0) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ der Gauß-Teststatistik ist definiert als

$$
	\varphi(X) := \begin{cases}
		1, \quad & T(X) \gt c \\
		0, \quad & T(X) \le c
	\end{cases}
$$

mit
- $T(X) \sim \mathcal{N}\left( \sqrt{n}\frac{a - a_0}{\sqrt{\sigma^2}}, 1 \right)$
- $c: = \phi^{-1}(1-\alpha)$
- $\forall x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n : \frac{f_{a_1}(x)}{f_{a_0}(x)} \lesseqqgtr k \iff T(x) \lesseqqgtr c$

Es gilt
- die [[zettel/_examples/Gütefunktion Normalverteilung|Gütefunktion]] von $\varphi(X)$ ist streng monoton wachsend
- $\forall a \le a_0 : \text{E}_a[\varphi(X)] \le \alpha$ $\implies$ $\varphi(X)$ ist der [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig beste]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ für das gegebene Testproblem