Das zu $F(x) = x, x \in \mathbb{R}$ gehörende [[Maß]] $\lambda$ heißt *Lebesgue-Borelsches Maß* auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$

Es gilt
- $\forall x \in \mathbb{R} : \lambda(\{ x \}) = 0$
- $\lambda([a, b]) = \lambda((a, b]) = \lambda([a, b)) = \lambda((a, b)) = b - a$

---

Zu jeder [[Korollar 1.17|Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}^d$ gibt es genau ein [[Maß]] $\lambda^d$, sodass
- $\lambda^d(S) = \Delta_S F = \Pi_{k = 1}^d (b_k - a_k)$ mit
- $S = \Pi_{i = 1}^d (a_1, b_1]$
- $\forall k \in {1, \dots, d} : -\infty \lt a_k \le b_k \lt +\infty$

---

Das Lebesgue Borelsche Maß ist [[Invarianzen|translations-]] und [[Invarianzen|spiegelungsinvariant]].

---

Sei $-\infty \lt a \le b \lt +\infty$, $x \in \mathbb{R}$, $f : [a, b] \to \mathbb{R}_+$ eine Riemann-integrierbare Funktion mit
- $\int_a^b f(t) dt = 1$

Die [[Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ eines [[Maß|Wahrscheinlichkeitsmaßes]] $P$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$ ist definiert als

$$
	F(x) = \begin{cases}
		0, \quad\quad\quad\quad\quad x \le a \\
		\int_a^x f(t) dt, \quad a \lt x \le b \\
		1, \quad\quad\quad\quad\quad x \gt b
	\end{cases}
$$

---

Sei $x \in \mathbb{R}$, $f : \mathbb{R} \to \mathbb{R}_+$ eine uneigentlich Riemann-integrierbare Funktion mit
- $\int_{-\infty}^{+\infty} f(t) dt = 1$

Die [[Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ eines [[Maß|Wahrscheinlichkeitsmaßes]] $P$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$ ist definiert als

$$
	F(x) = \int_{-\infty}^x f(t) dtcd
$$
