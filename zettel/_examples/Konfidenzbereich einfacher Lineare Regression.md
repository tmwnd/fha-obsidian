Sei $(Z_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(0, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $a, b, (y_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}$ beliebig, $X_i := a + by_i + Z_i$, $\alpha := a + b\overline{y}$, $\beta := b\sigma_y$, $(t_i)_{i \in \{ 1, \dots, n \}} := \left( \frac{y_i - \overline{y}}{\sigma_y} \right)_{i \in \{ 1, \dots, n \}}$, $1-\alpha$ das vorgegebene Konfidenznivaeu mit
- $\sigma^2 \gt 0$ unbekannt
- $a, b \in \mathbb{R}$ unbekannt
- $(y_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}$ bekannt
- $\exists i, j \in \{ 1, \dots, n \} : y_i \ne y_j$

Es gilt
- $\overline{X} = \frac{1}{n} \sum_{i=1}^n X_i$
- $\overline{Xt} = \frac{1}{n} \sum_{i=1}^n X_it_i$
- $\overline{X^2} = \frac{1}{n} \sum_{i=1}^n X_i^2$

und

$$
	\forall i \in \{ 1, \dots, n \} : X_i = \alpha + \beta t_i + Z_i
$$

Die [[zettel/Schätzer|Schätzer]] der [[zettel/Maximum-Likelihood-Schätzfunktion|Maximum-Likelihood-Schätzfunktionen]] $\hat{\alpha}(X), \hat{\beta}(X), \hat{\sigma}^2(X)$ sind definiert als

$$
	\hat{\alpha}(X) = \overline{X}
$$

bzw.

$$
	\hat{\beta}(X) = \overline{Xt}
$$

bzw.

$$
	\hat{\sigma}^2(X) = \frac{1}{n} \sum_{i=1}^n (X_i - (\hat{\alpha}(X) - \hat{\beta}(X)t_i)^2) = \overline{X^2} - \overline{X}^2 - \overline{Xt}^2
$$

Es gilt
- $\overline{\alpha}(X) \sim \mathcal{N}(\alpha, \frac{\sigma^2}{n})$
- $\overline{\beta}(X) \sim \mathcal{N}(\beta, \frac{\sigma^2}{n})$
- $\frac{n\hat{\sigma}^2(X)}{\sigma^2} \sim \chi_{n-2}^2$
- $\hat{\alpha}(X) + \hat{\beta}(X)t_0 \sim \mathcal{N}(\alpha + \beta t_0, \frac{\sigma^2}{n}(1+t_0^2))$
- $\hat{\alpha}(X), \hat{\beta}(X), \hat{\sigma}^2(X)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]]

sodass

$$
	\frac{\hat{\alpha}(X) + \hat{\beta}(X)t_0 - (\alpha + \beta t_0)}{\sqrt{\frac{\sigma^2}{n}(1+t_0^2)}} \sim \mathcal{N}(0, 1)
$$

und

$$
	\frac{\hat{\alpha}(X) + \hat{\beta}(X)t_0 - (\alpha + \beta t_0)}{\sqrt{\frac{\hat{\sigma}^2(X)}{n-2}(1+t_0^2)}} \sim t_{n-2}
$$

und

$$
	1-\alpha = P_{\alpha, \beta, \sigma^2}\left(\left| \frac{\hat{\alpha}(X) + \hat{\beta}(X)t_0 - (\alpha + \beta t_0)}{\sqrt{\frac{\hat{\sigma}^2(X)}{n-2}(1+t_0^2)}} \right| \le c \right) = P_{\alpha, \beta, \sigma^2}\left( \hat{\alpha}(X) + \hat{\beta}(X)t_0 - c\sqrt{\frac{\hat{\sigma}^2(X)}{n-1} (1+t_0^2)} \le \alpha + \beta t_0 \le \hat{\alpha}(X) + \hat{\beta}(X)t_0 + c\sqrt{\frac{\hat{\sigma}^2(X)}{n-1} (1+t_0^2)} \right)
$$

mit
- $c := t_{n-1, 1-\frac{\alpha}{2}}$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $\alpha + \beta t_0$ mit dem Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \hat{\alpha}(X) + \hat{\beta}(X)t_0 - c\sqrt{\frac{\hat{\sigma}^2(X)}{n-1} (1+t_0^2)}, \quad \hat{\alpha}(X) + \hat{\beta}(X)t_0 + c\sqrt{\frac{\hat{\sigma}^2(X)}{n-1} (1+t_0^2)} \right]
$$

Es gilt
- $\hat{a}(X) = \hat{\alpha}(X) - \hat{\beta}(X) \frac{\overline{y}}{\sigma_y}$
- $\hat{b}(X) = \frac{\hat{\beta}(X}{\sigma_y}$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $a + by_0$ mit dem Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \hat{a}(X) + \hat{b}(X)y_0 - c \sqrt{\frac{\sigma^2}{n-2} \left( 1 + \frac{(y_0 - \overline{y})^2}{\sigma_y^2} \right)}, \quad \hat{a}(X) + \hat{b}(X)y_0 + c \sqrt{\frac{\sigma^2}{n-2} \left( 1 + \frac{(y_0 - \overline{y})^2}{\sigma_y^2} \right)} \right]
$$

Es gilt

$$
	1-\alpha = P_{\alpha, \beta, \sigma^2}\left( (\hat{\alpha}(X) - \alpha)^2 + (\hat{\beta}(X) - \beta)^2 \le \frac{2}{n-2} F_{2, n-2, 1-\alpha} \hat{\sigma}^2(X) \right)
$$

sodass

$$
	\forall t \in \mathbb{R} : |\hat{\alpha}(X) - \alpha) + (\hat{\beta}(X) - \beta)t| \le \sqrt{1+t^2}\sqrt{(\hat{\alpha}(X) - \alpha)^2 + (\hat{\beta}(X) - \beta)^2}
$$

und

$$
	\forall \alpha, \beta \in \mathbb{R}, \sigma^2 \gt 0 : P_{\alpha, \beta, \sigma^2}\left( \forall t \in \mathbb{R} : |\hat{\alpha}(X) + \hat{\beta}(X)t - (\alpha + \beta t)| \le \sqrt{\frac{2}{n-2} F_{2, n-2, 1-\alpha} \hat{\sigma}^2(X)(1 - t^2)} \right) \ge 1-\alpha
$$

sodass die Grenzen des Konfidenzgürtelschätzers der Regressionsgeraden $\alpha + \beta t \mid t \in \mathbb{R}$ definiert sind als

$$
	\left. \hat{\alpha}(X) + \hat{\beta}(X)t \pm \sqrt{\frac{2}{n-2} F_{2, n-2, 1-\alpha} \hat{\sigma}^2(X) (1+t^2)} \ \right| \ t \in \mathbb{R}
$$