1. Eine Cauchy-verteilte Zufallsvariable $X$ hat die Fourier-Transformierte
	
	$$
		\varphi_X(z) = e^{-|z|}, \quad z \in \mathbb{R}
	$$
	
	Es seien $X_1, \dots, X_n$ unabhängig und jeweils Cauchy-verteilt.
	Berechnen Sie die Verteilung des arithmetischen Mittels $\overline{X} = \frac{1}{n}\sum_{j=1}^n X_j$ der $X_1, \dots, X_n$.

^1

2. Seien $X_1, X_2, \dots, Y_1, Y_2, \dots$ unabhängige, je $\text{Exp}(1)$-verteilte Zufallsvariablen.
	Seien $\overline{X}_m := \frac{1}{m}\sum_{k=1}^m X_k$, $\overline{Y}_n := \frac{1}{n}\sum_{k=1}^n Y_k$ die arithmetischen Mittel.
	Ziegen Sie, dass im Falle $\lim_{m, n \to \infty} \frac{n}{n+m} = \tau \in [0, 1]$
	
	$$
		\sqrt{\frac{mn}{m+n}}(\overline{X}_m - \overline{Y}_n) \overset{V}{\longrightarrow} N(0, 1), \quad m, n \to \infty
	$$
	
	gilt.

^2

3. Ein Gerät enthält ein elektronisches Element, dessen Funktionieren für die Arbeit des Gerätes erforderlich ist.
	Fällt dieses Element aus, so wird es soft durch ein Reserveelement ersetzt.
	Die Lebensdauern dieser Elemente können als unabhängige und identisch verteilte Zufallsvariablen mit dem Erwartungswert $\mu = 100 [\text{h}]$ und der Varianz $\sigma^2 = 3600 [\text{h}^2]$ aufgefaßt werden.
	Bestimmen Sie näherungsweise die Anzahl der Elemente, die erforderlich sind, um mit einer Wahrscheinlichkeit von mindestens $0,9$ eine ununterbrochene Arbeit von $t = 8000 [\text{h}]$ des Gerätes garantieren zu können.

^3

4. Es seien $X_1, X_2$ unabhängige und identisch verteilte reelle Zufallsvariablen mit $E(X_1) = 0$ und $\text{Var}(X_1) = 1$.
	Zeigen Sie:
	
	$$
		\frac{X_1 + X_2}{\sqrt{2}} \overset{V}{=} X_1 \iff X_1 \sim N(0, 1)
	$$

^4