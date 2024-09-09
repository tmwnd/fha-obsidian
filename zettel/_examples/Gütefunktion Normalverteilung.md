Seien $X = (X_i)_{i \in \{ 1 \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $\mu_0 \in \mathbb{R}$ beliebig.

Die [[zettel/Gütefunktion|Gütefunktion]] von $X$ ist definiert als

$$
	a \mapsto \text{E}_\mu[\varphi(X)] := P_\mu(T(X) \gt c) = 1 - \phi\left( c - \sqrt{n}\frac{\mu - \mu_0}{\sqrt{\sigma^2}} \right)
$$