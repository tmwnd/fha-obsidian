1. Ist

	$$
		F(x) = \begin{cases}
			0, \quad\quad\quad\quad\ \ x \lt 0 \\
			1 - \frac{1}{2}e^{-x}, \quad x \ge 0
		\end{cases}
	$$
	
	die Verteilungsfunktion eines Wahrscheinlichkeitsmaßes auf der Borelschen $\sigma$-Algebra $\mathfrak{B}$ von $\mathbb{R}$?
	
	Für $a \in \mathbb{R}$ sei
	
	$$
		\delta_a(B) = \begin{cases}
			1, \quad a \in B \\
			0, \quad a \notin B
		\end{cases}
	$$
	
	mit $B \in \mathfrak{B}$, das Dirac- oder Einpunktmaß auf der Borelschen $\sigma$-Algebra $\mathfrak{B}$.
	Skizzieren Sie die Verteilungsfunktionen der folgenden Wahrscheinlichkeitsmaße $P$ auf der Borelschen $\sigma$-Algebra $\mathfrak{B}$ von $\mathbb{R}$:
	1. $P = \delta_a$, $a \in \mathbb{R}$
	2. $P = p\delta_0 + (1-p)\delta_1$, $p \in (0, 1)$

^1

2. 
	- a) Zeigen Sie, dass die Verteilungsfunktion $F$ eines Wahrscheinlichkeitsmaßes $P$ auf der Borelschen $\sigma$-Algebra $\mathfrak{B}$ genau dann stetig in $x \in \mathbb{R}$ ist, wenn $P(\{ x \}) = 0$ gilt.
	- b) Zeigen Sie, dass es höchstens abzählbar viele $x \in \mathbb{R}$ gibt mit $P(\{ x \}) \gt 0$

^2

3. Zeigen Sie: Ist $F$ eine Verteilungsfunktion, so ist bei beliebigem $h \ne 0$ die Funktion $G(x) = \frac{1}{h}\int_x^{x+h} F(t) dt$, $x \in \mathbb{R}$, ebenfalls eine Verteilungsfunktion.

^3

4. Es seien $F_1, F_2$ eindimensionale Verteilungsfunktionen.
	Zeigen Sie, dass für jedes $\vartheta \in [-1, +1]$ durch
	
	$$
		T(x, y) := F_1(x)F_2(x)(1 + \vartheta(1 - F_1(x))(1 - F_2(x))), \quad x, y \in \mathbb{R}
	$$
	
	eine zweidimensionale Verteilungsfunktion definiert wird.

^4