Sei $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(a, \sigma^2) \mid n \in \mathbb{N}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $a_0 \in \mathbb{R}$ beliebig, $\text{H} : a \le a_0, \text{K} : a \gt a_0$ ein [[zettel/Einseitiges statistisches Testproblem|einseitiges statistisches Testproblem]], $\vartheta(X)$ der [[zettel/Statistischer Test|statistische Test]] der [[zettel/Gauß-Teststatistik|Gauß-Teststatistik]] mit
- $a$ unbekannt
- $\sigma^2$ bekannt

Die Dichte von $X$ ist definiert als

$$
	f_a(x) := \left. \left( \frac{1}{\sqrt{2\pi\sigma^2}} \right)^n \exp\left( -\frac{1}{2\sigma^2} \sum_{i=1}^n (x_i - a)^2 \right) \ \right| \ x = (x_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}^n
$$

Da die [[zettel/_examples/Gütefunktion Normalverteilung|Gütefunktion]] von $\vartheta(X)$ streng monoton wachsend ist, gilt
- $\varphi(X)$ ist der [[zettel/Statistischer Test/Gleichmäßige Bestheit|gleichmäßig beste]] [[zettel/Statistischer Test|statistische Test]] für das gegebene Testproblem