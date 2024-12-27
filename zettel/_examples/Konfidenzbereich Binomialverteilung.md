Sei $X \sim \mathfrak{B}(n, p)$, $1-\alpha$ das vorgegebene Konfidenzniveau mit
- $n \in \mathbb{N}$ bekannt
- $p \in (0, 1)$ unbekannt

Es gilt

$$
	1-\alpha = \lim_{n \to \infty} P_p\left( \underbrace{\left| \frac{X - np}{\sqrt{np(1-p)}} \right|}_{\overset{V}{\longrightarrow} |Y|, Y \sim \mathcal{N}(0,1)} \le c \right) = \lim_{n \to \infty} P_p\left( \frac{\frac{X}{n} + \frac{c^2}{2n} - \frac{c}{\sqrt{n}}\sqrt{\frac{X}{n}(1 - \frac{X}{n} + \frac{c^2}{4n})}}{1 + \frac{c^2}{n}} \le p \le \frac{\frac{X}{n} + \frac{c^2}{2n} + \frac{c}{\sqrt{n}}\sqrt{\frac{X}{n}(1 - \frac{X}{n} + \frac{c^2}{4n})}}{1 + \frac{c^2}{n}} \right)
$$

mit
- $c := \phi^{-1}(1-\frac{\alpha}{2})$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $p$ mit dem asymptotisch eingehaltenen Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \frac{\frac{X}{n} + \frac{c^2}{2n} - \frac{c}{\sqrt{n}}\sqrt{\frac{X}{n}(1 - \frac{X}{n} + \frac{c^2}{4n})}}{1 + \frac{c^2}{n}}, \quad \frac{\frac{X}{n} + \frac{c^2}{2n} + \frac{c}{\sqrt{n}}\sqrt{\frac{X}{n}(1 - \frac{X}{n} + \frac{c^2}{4n})}}{1 + \frac{c^2}{n}} \right]
$$

Analog gilt

$$
	1-\alpha = \lim_{n \to \infty} P_p\left(\left| \frac{X - np}{\sqrt{X (1-\frac{X}{n})}} \right| \le c \right) = \lim_{n \to \infty} P_p\left( \frac{X}{n} - \frac{c}{\sqrt{n}} \sqrt{\frac{X}{n} \left( 1 - \frac{X}{n} \right)} \le p \le \frac{X}{n} + \frac{c}{\sqrt{n}} \sqrt{\frac{X}{n} \left( 1 - \frac{X}{n} \right)} \right)
$$

mit
- $c := \phi^{-1}(1-\frac{\alpha}{2})$

Der [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]] $B(X)$ für $p$ mit dem asymptotisch eingehaltenen Konfidenzniveau $1-\alpha$ ist definiert als

$$
	B(X) := \left[ \frac{X}{n} - \frac{c}{\sqrt{n}} \sqrt{\frac{X}{n} \left( 1 - \frac{X}{n} \right)}, \quad \frac{X}{n} + \frac{c}{\sqrt{n}} \sqrt{\frac{X}{n} \left( 1 - \frac{X}{n} \right)} \right]
$$