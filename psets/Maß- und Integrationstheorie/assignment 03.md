1. Sei $f : (X, \mathcal{A}) \to Y$ eine Abbildung aus dem messbaren Raum $(X, \mathcal{A})$.
	Zeigen Sie, dass dann durch
	
	$$
		\mathcal{B}_f := \{ B \subseteq Y \mid f^{-1}(B) \in A \}
	$$
	
	eine $\sigma$-Algebra auf $Y$ erzeugt wird.

^1

2. Sei $f : (X, \mathcal{A}) \to (Y, \mathcal{B})$ eine messbare Abbildung und $\mathcal{B}_f$ wie unter [[psets/Maß- und Integrationstheorie/assignment 03#^1|1.]] definiert.
	Zeigen Sie:
	1. $\mathcal{B} \subseteq \mathcal{B}_f$
	2. $f^{-1}(\mathcal{B}) \subseteq f^{-1}(\mathcal{B}_f) \subseteq \mathcal{A}$

^2

3. Sei $X \ne \emptyset$ und $\mathcal{A} = \{ \emptyset, X \}$ die triviale $\sigma$-Algebra auf $X$.
	Ferner sei $Y \ne \emptyset$ versehen mit der $\sigma$-Algebra $\mathcal{B} := \mathcal{P}(Y)$.
	Bestimmen Sie alle messbaren Abbildung $f : (X, \mathcal{A}) \to (Y, \mathcal{B})$.

^3

4. Beweisen Sie.
	
	Sei $(X, \mathcal{A})$ ein messbarer Raum und $A \subseteq X$.
	Dann ist äquivalent:
	1. $I_A$ ist $\mathcal{A}$-messbar
	2. $A \in \mathcal{A}$

^4

5. Sei $f : (\mathbb{R}, \mathcal{B}^*) \to (\mathbb{R}, \mathcal{B}^*)$ eine monotone Funktion.
	Zeigen Sie, dass $f$ $\mathcal{B}^*$-messbar ist.

^5

6. Bestimmen Sie Postitiv- und Negativteil der Funktion $\sin : (\mathbb{R}, \mathcal{B}^*) \to (\mathbb{R}, \mathcal{B}^*)$.

^6

7. Sei $f : (X, \mathcal{A}) \to (Y, \mathcal{B})$ eine messbare Abbildung und $C \subseteq X$ eine beliebige Menge, die nicht notwendigerweise in $\mathcal{A}$ liegen muss.
	
	1. Zeigen Sie zunächst, dass das Mengensystem $\mathcal{A}_C := \{ A \cap C \mid A \in \mathcal{A} \}$ eine $\sigma$-Algebra auf $C$ ist.
	2. Durch $f|_C : (C, \mathcal{A}_C) \to (Y, \mathcal{B})$ mit $f|_C(x) : f(x)$, für $x \in C$, wird dann die Restriktion von $f$ auf $C$ definiert.
		Zeigen Sie, dass aus der $(\mathcal{A}, \mathcal{B})$-Messbarkeit von $f$ die $(\mathcal{A}_C, \mathcal{B})$-Messbarkeit von $f|_C$ folgt.

^7

8. Mit $f, g \in \overline{Z(X, \mathcal{A})}$ ist auch $\frac{f}{g}$, falls definiert, $\mathcal{A}$-messbar.

^8

9. Gegeben sei die Funktion $f : (\mathbb{R}, \mathcal{B}^*) \to (\mathbb{R}, \mathcal{B}^*)$, mit $f(x) = 3 \cdot I_{(-\infty, 0]} + 9 \cdot I_{[0, \infty)}$.
	Dies ist offensichtlich die Normaldarstellung.
	Geben Sie eine weitere Darstellung von $f$ an, die keine Normaldarstellung ist.

^9

10. Sei $f \in E(X, \mathcal{A})$ eine nicht-negative Elementarfunktion und $\alpha \ge 0$.
	Zeigen Sie, dass $\alpha \cdot f \in E(X, \mathcal{A})$ ebenfalls eine nicht-negative Elementarfunktion ist, für die zusätzlich nicht gilt:
	
	$$
		\int \alpha \cdot f d\mu = \alpha \int f d\mu
	$$

^10

11. Beweisen Sie.
	
	Es seien $f, g \in \overline{Z(X, \mathcal{A})}$ zwei nicht-negative Funktionen.
	Dann gilt:
	1. $\int \alpha \cdot f d\mu = \alpha \cdot \int f d\mu, \quad \forall \alpha \ge 0$
	2. $\int (f+g) d\mu = \int f d\mu + \int g d\mu$

^11

12. Beweisen Sie.
	
	Sei der Maßraum $((0, 1], \mathcal{B}_{(0, 1]}^*, \lambda)$ gegeben mit dem Lebesgue-Maß $\lambda$ auf dem Einheitsintervall.
	Dabei bezeichnet $\mathcal{B}_{(0, 1]}^* := \{ (0, 1] \cap B \mid B \in \mathcal{B}^* \}$ die $\sigma$-Algebra, die entsteht, wenn man die Borelmengen mit dem Intervall $(0, 1]$ schneidet vgl. [[psets/Maß- und Integrationstheorie/assignment 03#^7|7.]].
	Die Messbare Funktion
	
	$$
		f : ((0, 1], \mathcal{B}_{(0, 1]}^*) \to (\mathbb{R}, \mathcal{B}^*), \quad f(x) := \sum_{n=1}^\infty (-1)^n \cdot n \cdot (n+1) \cdot I_{(\frac{1}{n+1}, \frac{1}{n}]}
	$$
	
	ist weder integrierbar noch quasiintigrierbar.

^12

13. Sei $f : (0, 1] \to \mathbb{R}, f(x) := x^2$, $(f_n)_{n \in \mathbb{N}} \subseteq E_+((0, 1], \mathcal{B}_{(0, 1]}^*)$ eine Folge von nicht-negativen Elementarfunktionen mit
	
	$$
		f_n(x) := \sum_{k=1}^{2^n} \frac{(k-1)^2}{2^{2n}} \cdot I_{A_{n, k}}(x), \text{ mit } A_{n, k} := \left( \frac{k-1}{2^n}, \frac{k}{2^n} \right]
	$$
	
	wobei $k = 1, \dots, 2^n$, $n \in \mathbb{N}$.
	
	Zeigen Sie, dass $(f_n)_{n \in \mathbb{N}}$ monoton wachsend ist und gegen $f$ gleichmäßig konvergiert.

^13

14. Gegeben sei der Lebesguesche-Maßraum auf dem Einheitsintevall, d. h. $([0, 1], \mathcal{B}_{[0, 1]}^*, \lambda)$.
	Konstruieren Sie eine Folge $(f_n)_{n \in \mathbb{N}}$ von nicht-negativen Funktionen aus $\overline{Z([0, 1], \mathcal{B}_{[0, 1]}^*)}$ mit der Eigenschaft, dass $f_n(x) \to 0$, $\lambda$-f. s. auf $[0, 1]$, und $\lim_{n \to \infty} \int f_n d\lambda = 0$.

^14

15. Sei zu jedem $n \in \mathbb{N}$ $(a_{n, k})_{k \in \mathbb{N}}$ eine reelle Zahlenfolge mit der Eigenschaft, dass $\lim_{n \to \infty} a_{n, k} = a_k$.
	Ferner Sei $(b_k)_{k \in \mathbb{N}}$ eine weitere reelle Zahlenfolge mit $|a_{n, k}| \le b_k$ für alle $n, k \in \mathbb{N}$, für die zusätzlich noch $\sum_{k=1}^\infty b_k \lt \infty$.
	Zeigen Sie, dass dann für alle $n \in \mathbb{N}$ $\sum_{k=1}^\infty |a_{k, n}| \lt \infty$ und dass
	
	$$
		\lim_{n \to \infty} \sum_{k=1}^\infty a_{n, k} = \sum_{k=1}^\infty \lim_{n \to \infty} a_{n, k} = \sum_{k=1}^\infty a_k
	$$

^15

16. Gegeben seien $(x_i)_{i=1}^\infty$ und $(y_i)_{i=1}^\infty$ reelle quadratsummierbare Folgen.
	Zeigen Sie die folgende Ungleichung:
	
	$$
		\left( \sum_{i=1}^\infty (x_i + y_i)^2 \right)^\frac{1}{2} \le \left( \sum_{i=1}^\infty x_i^2 \right)^\frac{1}{2} + \left( \sum_{i=1}^\infty y_i^2 \right)^\frac{1}{2}
	$$

^16

17. Gegeben seien $(x_i)_{i=1}^n \subset \mathbb{R}$ und $(y_i)_{i=1}^n \subset \mathbb{R}$.
	Zeigen Sie die folgende Ungleichung:
	
	$$
		\sum_{i=1}^n |x_i \cdot y_i| \le \left( \sum_{i=1}^n x_i^2 \right)^\frac{1}{2} \cdot \left( \sum_{i=1}^n y_i^2 \right)^\frac{1}{2}
	$$

^17

18. Zeigen Sie, dass für $f, g \in L_1(X, \mathcal{A}, \mu)$ mit
	
	$$
		\int_A f d\mu = \int_A g d\mu, \quad \forall A \in \mathcal{A}
	$$
	
	gilt: $f = g$, $\mu$-f. s..

^18

19. Sei $(X, \mathcal{A}, \mu)$ ein Maßraum und $1 \le p \le q \le \infty$.
	Man zeige:
	1. Im Fall $\mu(X) \lt \infty$ gilt $L_q(X, \mathcal{A}, \mu) \subseteq L_p(X, \mathcal{A}, \mu)$.
	2. Gilt obige Aussage auch im Fall $\mu(X) = \infty$?
	3. Seien $p, q$ wie oben, $\mu(X) \lt \infty$ und $(f_n)_{n \in \mathbb{N}} \subseteq L_q(X, \mathcal{A}, \mu)$.
		Dann gilt: $\| f_n - f \|_q \to 0 \implies \| f_n - f \|_p \to 0$

^19

20. Sei $(f_n)_{n \in \mathbb{N}} \subseteq Z_+(X, \mathcal{A})$ beliebig und $1 \le p \lt \infty$.
	Dann gilt
	
	$$
		\left\| \sum_{i=1}^\infty f_i \right\|_p \le \sum_{i=1}^\infty \| f_i \|_p
	$$

^20

21. Auf einem *metrischen Raum*, also einem Tupel $(E, d)$, $d$ Metrik, definiert man die Stetigkeit einer Abbildung $f : R \to \mathbb{R}$ analog zum reellen Fall: $f$ heißt *stetig* in $x_o \in E$, falls
	
	$$
		\forall \varepsilon \gt 0 \exists \delta \gt 0 : |f(x) - f(x_0)| \lt \varepsilon \text{ für } d(x, x_0) \lt \delta
	$$
	
	Beweisen Sie:
	1. Sei $(X, \mathcal{A}, \mu)$ ein Maßraum und $E$ ein metrischer Raum.
		Es sei weiter $f : X \times R \to \mathbb{R}$ eine Funktion mit den folgenden Eigenschaften:
		1. Die Funktion $x \to f(x, y)$ ist $\mu$-integrierbar für alle $y \in E$.
		2. Die Funktion $y \to f(x, y)$ ist stetig in $y_0 \in E \forall x \in X$.
		3. Es existiert eine $\mu$-integrierbare Funktion $g \ge 0$ auf $X$ mit $|f(x, y)| \le g(x) \forall x \in X, y \in E$.
	
		Dann ist die Funktion $\varphi : E \to \mathbb{R}$,
		
		$$
			\varphi(y) := \int f(x, y) \mu(dx)
		$$
		
		stetig in $y_0$.
		
		*Hinweis*: Verwenden Sie den Satz über die majorisierte Konvergenz von Lebesgue.
	2. Folgern Sie: Unter den oben genannten Voraussetzungen gilt
		
		$$
			\lim_{n \to \infty} \int f(x, y_n) \mu(dx) = \int \lim_{n \to \infty} f(x, y_n) \mu(dx) = \int f(x, y_0) y(dx)
		$$
		
		für jede Folge $(y_n)_{n \in \mathbb{N}} \subseteq E$ mit $d(y_n, y_0) \to 0$, $n \to \infty$.

^21