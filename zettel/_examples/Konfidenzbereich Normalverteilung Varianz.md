Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \in \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $1-\alpha$ das vorgegebene Konfidenzniveau mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma^2 \gt 0$ unbekannt

Es gilt
- $\overline{X} = \frac{1}{n} \sum_{i=1}^n X_i$
- $s^2 = \sum_{i=1}^n (X_i - \overline{X})^2$

und

$$
	\frac{s^2}{\sigma^2} \sim \chi_{n-1}^2
$$

sodass

$$
	1-\alpha = P_{\mu, \sigma^2}\left( \chi_{n-1, \frac{\alpha}{2}}^2 \le \frac{s^2}{\sigma^2} \le \chi_{n-1, 1-\frac{\alpha}{2}}^2 \right) = P_{\mu, \sigma^2}\left( \frac{s^2}{\chi_{n-1, 1-\frac{\alpha}{2}}^2} \le \sigma^2 \le \frac{s^2}{\chi_{n-1, \frac{\alpha}{2}}^2} \right)
$$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $\sigma^2$ mit dem Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \frac{s^2}{\chi_{n-1, 1-\frac{\alpha}{2}}^2}, \quad \frac{s^2}{\chi_{n-1, \frac{\alpha}{2}}^2} \right]
$$