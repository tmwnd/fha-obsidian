Seien $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $\mu_0 \in \mathbb{R}$ beliebig, $\text{H} : \mu = \mu_0, \text{K} : \mu \ne \mu_0$ ein [[zettel/Zweiseitiges statistisches Testproblem|zweiseitiges statistisches Testproblem]], $T(X)$ die [[zettel/Gauß-Teststatistik|Gauß-Teststatistik]], $\alpha$ das vorgegebene Testniveau mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma^2 \gt 0$ bekannt

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ des gegebenen statistischen Testproblems ist definiert als

$$
	\varphi(X) = \begin{cases}
		1, \quad & |T(X)| \gt c \\
		0, \quad & |T(X)| \le c
	\end{cases}
$$

mit
- $c := \phi^{-1}(1-\frac{\alpha}{2})$
- $\text{E}_{\mu_0}[\varphi(X)] = P_{\mu_0}(T(X) \gt c) + P_{\mu_0}(T(X) \le -c) = \frac{\alpha}{2} + \frac{\alpha}{2} = \alpha$ $\implies$ $\varphi(X)$ ist der [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig beste]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ für das gegebene Testproblem
- $\varphi(X)$ [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig bester]] [[zettel/Statistischer Test|statistische Test]] zum Testniveau $\alpha$ aller [[zettel/Statistischer Test/Unverfälschtheit|unverfälschten]] [[zettel/Statistischer Test|statistischen Tests]]