Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \in \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $1-\alpha$ das vorgegebene Konfidenzniveau mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma^2 \gt 0$ unbekannt

Es gilt
- $\overline{X} = \frac{1}{n} \sum_{i=1}^n X_i$
- $s^2 = \sum_{i=1}^n (X_i - \overline{X})^2$

und

$$
	\sqrt{n} \cdot \frac{\overline{X} - \mu}{\sqrt{\frac{1}{n-1}s^2}} \sim t_{n-1}
$$

sodass

$$
	1 - \alpha = P_{\mu, \sigma^2}\left( \sqrt{n} \frac{|\overline{X} - \mu|}{\sqrt{\frac{1}{n-1}s^2}} \le t_{n-1, 1-\frac{\alpha}{2}} \right) = P_{\mu, \sigma^2}\left( \overline{X} - \frac{t_{n-1, 1-\frac{\alpha}{2}}}{\sqrt{n}} \sqrt{\frac{1}{n-1}s^2} \le \mu \le \overline{X} + \frac{t_{n-1, 1-\frac{\alpha}{2}}}{\sqrt{n}} \sqrt{\frac{1}{n-1}s^2} \right)
$$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $\mu$ mit dem Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \overline{X} - \frac{t_{n-1, 1-\frac{\alpha}{2}}}{\sqrt{n}} \sqrt{\frac{1}{n-1}s^2}, \quad \overline{X} + \frac{t_{n-1, 1-\frac{\alpha}{2}}}{\sqrt{n}} \sqrt{\frac{1}{n-1}s^2} \right]
$$