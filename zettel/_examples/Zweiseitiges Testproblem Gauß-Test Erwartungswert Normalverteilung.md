Sei $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(a, \sigma^2) \mid n \in \mathbb{N}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $a_0 \in \mathbb{R}$ beliebig, $\text{H} : a = a_0, \text{K} : a \ne a_0$ ein [[zettel/Zweiseitiges statistisches Testproblem|zweiseitiges statistisches Testproblem]], $T(X)$ die [[zettel/Gauß-Teststatistik|Gauß-Teststatistik]], $\alpha$ das vorgegebene Testniveau mit
- $a$ unbekannt
- $\sigma^2$ bekannt

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ des gegebenen statistischen Testproblems ist definiert als

$$
	\varphi(X) = \begin{cases}
		1, \quad & |T(X)| \gt c \\
		0, \quad & |T(X)| \le c
	\end{cases}
$$

mit
- $c: = \phi^{-1}(1 - \frac{\alpha}{2})$
- $\text{E}_{a_0}[\varphi(X)] = P_{a_0}(T(X) \gt c) + P_{a_0}(T(X) \le -c) = \frac{\alpha}{2} + \frac{\alpha}{2} = \alpha$ $\implies$ $\varphi(X)$ ist der [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig beste]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ für das gegebene Testproblem
- $\varphi(X)$ [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig bester]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ aller [[zettel/Statistischer Test/Unverfälschtheit|unverfälschten]] [[zettel/Statistischer Test|statistischen Tests]]