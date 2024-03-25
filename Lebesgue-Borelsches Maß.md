Das zu $F(x) = x, x \in \mathbb{R}$ gehörende [[Maß]] $\lambda$ heißt *Lebesgue-Borelsches Maß* auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$

Es gilt
- $\forall x \in \mathbb{R} : \lambda(\{ x \}) = 0$
- $\lambda([a, b]) = \lambda((a, b]) = \lambda([a, b)) = \lambda((a, b)) = F(b) - F(a) = b - a$

---

Zu jeder [[modules/sto1/Korollar 1.17|Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}^d$ gibt es genau ein [[Maß]] $\lambda^d$, sodass
- $\lambda^d(S) = \Delta_S F = \prod_{k = 1}^d (b_k - a_k)$ mit
- $S = \prod_{i = 1}^d (a_1, b_1]$
- $\forall k \in {1, \dots, d} : -\infty \lt a_k \le b_k \lt +\infty$

---

Das Lebesgue Borelsche Maß ist [[Invarianzen|translations-]] und [[Invarianzen|spiegelungsinvariant]].

---

Sei $-\infty \lt a \le b \lt +\infty$, $x \in \mathbb{R}$, $f : [a, b] \to \mathbb{R}_+$ eine Riemann-integrierbare [[Funktion]] mit
- $\int_a^b f(t) dt = 1$

Die [[Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ eines [[Maß|Wahrscheinlichkeitsmaßes]] $P$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$ ist definiert als

$$
	F(x) = \begin{cases}
		0, & x \le a \\
		\int_a^x f(t) dt, & a \lt x \le b \\
		1, & x \gt b
	\end{cases}
$$

---

Sei $x \in \mathbb{R}$, $f : \mathbb{R} \to \mathbb{R}_+$ eine uneigentlich Riemann-integrierbare [[Funktion]] mit
- $\int_{-\infty}^{+\infty} f(t) dt = 1$

Die [[Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ eines [[Maß|Wahrscheinlichkeitsmaßes]] $P$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$ ist definiert als

$$
	F(x) = \int_{-\infty}^x f(t) dtcd
$$

---

Jede stetige [[Funktion]] $f : \mathbb{R}^d \to \mathbb{R}^p$ ist $(\mathcal{L}^d, \mathcal{L}^p)$-[[A-S-Messbarkeit|messbar]].

---

$f : \Omega \to \overline{\mathbb{R}}$ ist genau dann $(\mathcal{A}, \overline{\mathcal{L}})$-[[A-S-Messbarkeit|messbar]], falls
- a) $\forall a \in \mathbb{R} : \{ f \gt a \} = \{ \omega \in \Omega, f(\omega) \gt a \}$ = $f^{-1}((a, +\infty]) \in \mathcal{A}$
- b) $\forall a \in \mathbb{R} : \{ f \ge a \} = \{ \omega \in \Omega, f(\omega) \ge a \}$ = $f^{-1}([a, +\infty]) \in \mathcal{A}$
- c) $\forall b \in \mathbb{R} : \{ f \lt b \} = \{ \omega \in \Omega, f(\omega) \lt b \}$ = $f^{-1}([-\infty, b)) \in \mathcal{A}$
- d) $\forall b \in \mathbb{R} : \{ f \le b \} = \{ \omega \in \Omega, f(\omega) \le b \}$ = $f^{-1}([-\infty, b]) \in \mathcal{A}$

a) $\iff$ b) $\iff$ c) $\iff$ d).

Schreibe
- $\{ f \in B \} = f^{-1}(B), B \subseteq R$.