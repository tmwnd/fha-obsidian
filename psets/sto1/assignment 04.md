1. Auf dem Rand eines Kreises mit dem Mittelpunkt im Koordinatenursprung und dem Radius $r$ werde zufällig und gleichwahrscheinlich ein Punkt ausgewählt (mit anderen Worten, der Polarwinkel des Punks ist eine $\mathfrak{R}(-\pi, +\pi)$-verteilte Zufallsvariable).
	Bestimmen Sie die Verteilungsfunktion der Abszisse des Punkts.

^1

2. 
	- a) Eine Zufallsvariable $X$ heißt Chauchy-verteilt mit den Parametern $\mu \in \mathbb{R}$ und $\sigma \in (0, \infty)$, falls $X$ die Verteilungsfunktion
		
		$$
			F(x) = \frac{1}{2} + \frac{1}{\pi}\arctan\left( \frac{x-\mu}{\sigma} \right), \quad x \in \mathbb{R}
		$$
		
		hat; schreibe $X \sim C(\mu, \sigma$.
		Es sei $X \sim C(0, 1)$.
		Bestimmen Sie die Verteilung von $\frac{1}{X}$.
	- b) Eine Zufallsvariable $X$ heißt Exponential-verteilt mit Parameter $\lambda \in (0, \infty)$, falls $X$ die Verteilungsfunktion
		
		$$
			F(x) = 1 - e^{-\lambda x}, \quad x \gt 0
		$$
		
		und $0$ sonst, hat; schreibe $X \sim \text{Exp}(\lambda)$.
		Es sei $U \sim \mathfrak{R}(0, 1)$.
		Zeigen Sie $-\log U \sim \text{Exp}(1)$

^2

3. Es sei $X$ eine reelle Zufallsvariable mit der Verteilungsfunktion $F$, $U \sim \mathfrak{R}(0, 1)$, $F^-1 : \mathbb{R} \to \mathbb{R}$ sei auf dem Intervall $(0, 1)$ festgelegt durch
	
	$$
		F^-1(u) = \inf\{ x \in \mathbb{R} \mid F(x) \ge u \}
	$$
	
	für $u \in (0, 1)$.
	
	- a) Bestimmen und skizzieren Sie $F^-1$ für die Verteilungen in [[assignment 02#^1|Aufgabe 1]] von [[assignment 02|Blatt 2]].
	- b) Zeigen Sie: Es haben $F^{-1} \circ U$ und $X$ dieselbe Verteilung.
	- c) Zeigen Sie: Es sei $F$ stetig.
		Dann haben $F \circ X$ und $U$ dieselbe Verteilung.
	- d) Beweisen Sie: $F^{-1}$ ist linksseitig stetig und monoton wachsend.

^3