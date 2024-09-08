Sei $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(a, \sigma^2) \mid n \in \mathbb{N}$ eine [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $a_0 \in \mathbb{R}$ beliebig.

Die [[zettel/Gütefunktion|Gütefunktion]] von $X$ ist definiert als

$$
	a \mapsto \text{E}_a[\varphi(X)] := P_a(T(X) \gt c) = 1 - \phi\left( c - \sqrt{n}\frac{a - a_0}{\sqrt{\sigma^2}} \right)
$$