1. Es sei $\alpha$ eine reele Zahl. $f : \mathbb{R} \to \mathbb{R}$ eine durch
	
	$$
		f(x) = \begin{cases}
			\alpha x^2(1-x), \quad 0 \le x \le 1, \\
			0, \quad\quad\quad\quad\quad\ \text{sonst}
		\end{cases}
	$$
	
	definierte Funktion.
	Es ist $\alpha$ so zu bestimmen, dass $f$ Wahrscheinlichkeitsdichte einer reelen Zufallsvariable $X$ ist.
	Gesucht sind $E(X)$, $P(X \le \frac{1}{2})$ und $P(X \lt E(X))$.

^1

2. Die reele Zufallsvariable $X$  habe die Dichte $f(x) = 1 - |1 - x|$ für $0 \le x \le 2$ und $0$ sonst.
	Bestimmen Sie $\text{Var}(X)$.

^2

3. Es sei $X$ eine reele Zufallsvariable mit dem Erwartungswert $0$ und der Varianz $0 \lt \sigma^2 \lt \infty$.
	Zeigen Sie mit der Cauchy-Schwarzen Ungleichung:
	
	$$
		P(X \le x) \le \frac{\sigma^2}{\sigma^2 + x^2}, \quad x \lt 0
	$$
	
	$$
		P(X \le x) \gt \frac{x^2}{\sigma^2 + x^2}, \quad x \gt 0
	$$
	
	Berechnen Sie die gennanten Schranken für $x = -3$ bzw. $x = 3$ im Fall $X = Z - 5$ mit $Z \sim \mathfrak{B}(10, \frac{1}{2})$ und vergleichen Sie diese mit den jeweiligen exakten Werten.

^3

4. 
	- a) Es sei $X \sim N(3, 2)$.
		Vergleichen Sie die aus der Chebyschevsche Ungleichung für $P(|X - 4| \le 4)$ erhaltene Abschätzung mit dem exakten Wert von $P(|X - 3| \le 4)$.
	- b) Ein echter Würfel wird $n$-mal unabhängig geworfen.
		Es sei $X_n$ die Anzahl der Würfe mit der Augenzahl $6$.
		Mit Hilfe der Chebyshevschen Ungleichung soll eine Zahl $n_0 \in \mathbb{N}$ angegeben werden mit der Eigenschaft, dass für jede Anzahl $n \ge n_0$ von Würfelwürfen die Wahrscheinlichkeit $P(\frac{17}{108}n \lt X_n \lt \frac{19}{108}n) \ge \frac{1}{2}$ ist.

^4

5. 
	- a) Es sei $X$ eine reele, nicht negative Zufallsvariable mit $0 \lt E(X^2) \lt \infty$.
		Zeigen Sie mit der Cauchy-Schwarzen Ungleichung: $P(X \gt 0) \ge \frac{E(X)^2}{E(X^2)}$.
	- b) Zeigen Sie mit der Cauchy-Schwarzen Ungleichung: Für eine positive reele Zufallsvariable mit $E(\frac{1}{X}) \lt \infty$ und $E(X) \lt \infty$ ist $E(\frac{1}{X}) \ge \frac{1}{E(X)}$.

^5