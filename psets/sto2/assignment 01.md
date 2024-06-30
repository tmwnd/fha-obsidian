1. Es seien $X_n$, $n \in \mathbb{N}$, reelle unabhängige Zufallsvariablen, je mit derselben Poissonverteilung $\mathfrak{P}(\lambda)$-Verteilung, $\lambda \gt 0$.
	Bestimmen Sie mit Hilfe des Fehlerfortpflanzungsgesetztes eine Funktion $f : \mathbb{R} \to \mathbb{R}$, so dass für alle $\lambda \gt 0$ gilt:
	
	$$
		\sqrt{n}\left( f\left( \frac{1}{n} \sum_{i=1}^n X_i \right) - f(\lambda) \right) \overset{v}{\longrightarrow} N(0, 1)
	$$

^1

2. Es seien $X_n$, $n \in \mathbb{N}$, reelle unabhängige Zufallsvariablen, je mit derselben $\mathfrak{B}(1, p)$-Verteilung.
	Bestimmen Sie eine Funktion $f : \mathbb{R} \to \mathbb{R}$, so dass für alle $p \in (0, 1)$ gilt:
	
	$$
		\sqrt{n}\left( f\left( \frac{1}{2} \sum_{i=1}^n X_i \right) - f(p) \right) \overset{v}{\longrightarrow} N(0, 1)
	$$

^2

3. Es seien $X_n$, $n \in \mathbb{N}$, reelle unabhängige und identisch verteilte Zufallsvariablen mit $E(X_n) = a \in \mathbb{R}$, $0 \lt \sigma^2 = \text{Var}[X_n] \lt \infty$.
	Es sei $\overline{X}_n = \frac{1}{n} \sum_{i=1}^n X_i$, $S_n^2 = \frac{1}{n} \sum_{i=1}^n (X_i - \overline{X}_n)^2$, $n = 1, 2, \dots$.
	Zeigen Sie:
	1. $S_n^2 \overset{P}{\longrightarrow} \sigma^2$
	2. Ist $\mu_4 := E((X_n - a)^4) \lt \infty$, so gilt $\sqrt{n}(S_n^2 - \sigma^2) \overset{v}{\longrightarrow} N(0, \tau^2)$ mit $\tau^2 = \mu_4 - \sigma^4$.
		Berechnen Sie $\tau^2$ für den Fall, dass $X_n \sim N(a, \sigma^2)$ ist.

^3