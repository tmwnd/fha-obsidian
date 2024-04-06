---
type: assignment
---

1. Es seinen $X, X_1, X_2, \dots, Y, Y_1, Y_2, \dots$ Zufallsvariablen auf einem Wahrscheinlichkeitsraum $(\Omega, \mathfrak{A}, P)$.
	Beweisen Sie die folgenden Implikationen:
	- a) $X_n \overset{P}{\longrightarrow} X$ und $Y_n \overset{P}{\longrightarrow} Y$ $\implies$ $X_n + Y_n \overset{P}{\longrightarrow} X + Y$
	- b) $X_n \overset{f. s.}{\longrightarrow} X$ und $Y_n \overset{f. s.}{\longrightarrow} Y$ $\implies$ $X_n + Y_n \overset{f. s.}{\longrightarrow} X + Y$

^1

2. Es sei $\{ X_n \}_{n \in \mathbb{N}}$ eine Folge von unabhängigen, je $\mathfrak{R}(0, 1)$-verteilten Zufallsvariablen.
	Es sei
	
	$$
		Z_n := \left( \prod_{k=1}^n X_k \right)^\frac{1}{n}
	$$
	
	das geometrische Mittel von $X_1, \dots, X_n$, $n \in \mathbb{N}$.
	Zeigen Sie die Existenz einer Konstanten $c \in \mathbb{R}$, so dass $Z_n \to c$ $P$-fast sicher gilt und bestimmen Sie $c$.

^2

3. Ein Spiele verfügt über ein Startkapital von $c\texteuro$.
	Bei einem Spiel mit Erfolgswahrscheinlichkeit $p \in (0, 1)$ setzt er einen teil seines Kapitals ein.
	Verliert er, so erhält die Bank seinen Einsatz, anderenfalls erhält der den doppelten Einsatz zurück.
	Für eine unbeschränkte Folge an Spielrunden (genauer, von unabhängigen Wiederholungen des Spiels) beschließt der Spieler folgende Strategie: Ist $X_k$ sein Kapital nach der $k$-ten Spielrunde, so sei $\alpha X_k$, $0 \lt \alpha \lt 1$, der Einsatz für die $(k+1)$-te Spielrunde, $k = 0, 1, \dots$, $X_0 = c$.
	Es sei $N_n$ die ANzahl der Gewinnrunden des Spielers in den ersten $n$ Spielrunden.
	- a) Zeigen Sie: $X_n = c(1 + \alpha)^{N_n}(1 - \alpha)^{1-N_n}$.
	- b) Konvergiert die Folge $(\frac{1}{n}\log X_n)_{n=1}^\infty$ fast sicher?
	- c) Berechnen Sie $E(X_n)$, untersuchen Sie, ob die Folge $(E(X_n))_{n=1}^\infty$ konvergiert und bestimmen Sie gegebenfalls den Grenzwert.

^3

4. Es sei $\varphi$ die Dichte der $N(0, 1)$-Verteilung, $\Phi(1) = \int_{-\infty}^1 \varphi(x) dx$.
	Gegeben seien Beobachtungen $u_1, \dots, u_n, v_1, \dots, v_n$ von unabhängigen, je $\mathfrak{R}(0, 1)$-verteilten Zufallsvariablen $U_1 \dots, U_n, V_1, \dots, V_n$.
	Begründen sie die Approximationen
	
	$$
		\frac{1}{2} + \frac{1}{n}\sum_{k=1}^n \varphi(u_k)
	$$
	
	und
	
	$$
		\frac{1}{2} + \frac{1}{n}\sum_{k=1}^n I(v_k \le \varphi(u_k))
	$$
	
	für $\Phi(1)$.
	Welche der beiden Approximationen ziehen Sie vor?
	Begründen Sie ihre Wahl.

^4