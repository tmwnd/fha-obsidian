1. Das Wahrscheinlichkeitsmaß $P$ auf $(\mathbb{R}, \mathfrak{B})$ habe die Dichte
	
	$$
		f(x) = \frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{(x - \mu)^2}{2\sigma^2}}, \quad x \in \mathbb{R}
	$$
	
	mit den Parametern $\mu \in \mathbb{R}$ und $\sigma \gt 0$.
	Es seien $a$ und $b$ die Abszissen der Wendepunkte von $f$
	Berechnen Sie $P([a, b])$.

^1

2. Das Wahrscheinlichkeitsmaß $P$ auf $(\mathbb{R}, \mathfrak{B})$ habe die Dichte
	
	$$
		f(x) = ae^{-\lambda|x|}, \quad -\infty \lt x \lt +\infty
	$$
	
	Dabei ist $\lambda \gt 0$ ein gegebener Parameter.
	
	- a) Bestimmen Sie den Koeffizienten $a$.
	- b) Stellen Sie die Dichte und die Verteilungsfunktion im Falle $\lambda = 1$ graphisch dar.

^2

3. Geben Sie ein Beispiel für $\lambda$-integrierbare Funktionen $f, f_n : (\mathbb{R}, \mathfrak{B}) \to (\mathbb{R}, \mathfrak{B})$, $n \in \mathbb{N}$, mit $f(x) = \lim_{n \to \infty} f(x)$ für jedes $x \in \mathbb{R}$ und
	
	$$
		\lim_{n \to \infty} \int f_n d\lambda \lt \int f d\lambda
	$$

^3

4. Es sei $(\Omega, \mathfrak{A}, \mu)$ ein Maßraum.
	Es sei $f : (\Omega, \mathfrak{A}) \to (\mathbb{R}, \mathfrak{B})$.
	Zeigen Sie:
	
	$$
		\sum_{n=1}^\infty \mu(\{ |f| \gt n \}) \le \int |f| d\mu \le \sum_{n=0}^\infty \mu(\{ |f| \gt n \})
	$$
	
	*Hinweis:* Es gilt offenbar
	
	$$
		\sum_{n=1}^\infty 1_{\{ |f| \gt n \}} \le |f| \le \sum_{n=0}^\infty 1_{\{ |f| \gt n \}}
	$$
	
	Durch Ausnutzung der Monotonie des Maßintegrals und des Satzes der Monotonen Konvergenz folgt die Behauptung.

^4