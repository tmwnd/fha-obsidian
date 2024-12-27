Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \sim \mathscr{P}(\lambda)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariable]], $S := \sum_{i=1}^n X_i$, $1-\alpha$ das vorgegebene Konfidenznivau mit
- $\lambda \in (0, \infty)$ unbekannt

Es gilt
- $\overline{X} = \frac{S}{n}$

und

$$
	1-\alpha = \lim_{n \to \infty} P_\lambda\left(\left| \frac{S - n\lambda}{\sqrt{n\lambda}} \right| \le c \right) = \lim_{n \to \infty} P_\lambda\left( \overline{X} + \frac{c^2}{2n} - \frac{c}{\sqrt{n}} \sqrt{\overline{X} + \frac{c^2}{4n}} \le \lambda \le \overline{X} + \frac{c^2}{2n} + \frac{c}{\sqrt{n}} \sqrt{\overline{X} + \frac{c^2}{4n}} \right)
$$

mit
$c := \phi^{-1}(1- \frac{\alpha}{2})$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $\lambda$ mit dem asymptotisch eingehaltenen Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \overline{X} + \frac{c^2}{2n} - \frac{c}{\sqrt{n}} \sqrt{\overline{X} + \frac{c^2}{4n}}, \quad \overline{X} + \frac{c^2}{2n} + \frac{c}{\sqrt{n}} \sqrt{\overline{X} + \frac{c^2}{4n}} \right]
$$

Analog gilt

$$
	1-\alpha = \lim_{n \to \infty} P_\lambda\left( \frac{S - n\lambda}{\sqrt{n\overline{X}}} \le c \right) = \lim_{n \to \infty} P_\lambda\left( \overline{X} - \frac{c}{\sqrt{n}} \sqrt{\overline{X}} \le \lambda \le \overline{X} + \frac{c}{\sqrt{n}} \sqrt{\overline{X}} \right)
$$

$c := \phi^{-1}(1- \frac{\alpha}{2})$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $\lambda$ mit dem asymptotisch eingehaltenen Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \overline{X} - \frac{c}{\sqrt{n}} \sqrt{\overline{X}}, \quad \overline{X} + \frac{c}{\sqrt{n}} \sqrt{\overline{X}} \right]
$$