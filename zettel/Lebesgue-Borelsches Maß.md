---
title: Lebesgue-Borelsches Maß
type: example
---

TODO stiejltjes

Das zu $F(x) = x, x \in \mathbb{R}$ gehörende [[zettel/Maß|Maß]] $\lambda$ heißt *Lebesgue-Borelsches Maß* auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathcal{L}$

Es gilt
- $\forall x \in \mathbb{R} : \lambda(\{ x \}) = 0$
- $\lambda([a, b]) = \lambda((a, b]) = \lambda([a, b)) = \lambda((a, b)) = F(b) - F(a) = b - a$

---

Zu jeder [[zettel/_corollaries/Korollar 1.17|Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathcal{L}^d$ gibt es genau ein [[zettel/Maß|Maß]] $\lambda^d$, sodass
- $\lambda^d(S) = \Delta_S F = \prod_{k = 1}^d (b_k - a_k)$ mit
- $S = \prod_{i = 1}^d (a_1, b_1]$
- $\forall k \in {1, \dots, d} : -\infty \lt a_k \le b_k \lt +\infty$

---

Das Lebesgue Borelsche Maß ist [[zettel/σ-Algebra/Translationsinvarianz|translations-]] und [[zettel/σ-Algebra/Spiegelungsinvarianz|spiegelungsinvariant]].

---

Sei $-\infty \lt a \le b \lt +\infty$, $x \in \mathbb{R}$, $f : [a, b] \to \mathbb{R}_+$ eine Riemann-integrierbare [[zettel/Funktion|Funktion]] mit
- $\int_a^b f(t) dt = 1$

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ eines [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaßes]] $P$ auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathcal{L}$ ist definiert als

$$
	F(x) = \begin{cases}
		0, & x \le a \\
		\int_a^x f(t) dt, & a \lt x \le b \\
		1, & x \gt b
	\end{cases}
$$

---

Sei $x \in \mathbb{R}$, $f : \mathbb{R} \to \mathbb{R}_+$ eine uneigentlich Riemann-integrierbare [[zettel/Funktion|Funktion]] mit
- $\int_{-\infty}^{+\infty} f(t) dt = 1$

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ eines [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaßes]] $P$ auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathcal{L}$ ist definiert als

$$
	F(x) = \int_{-\infty}^x f(t) dtcd
$$

---

Jede stetige [[zettel/Funktion|Funktion]] $f : \mathbb{R}^d \to \mathbb{R}^p$ ist $(\mathcal{L}^d, \mathcal{L}^p)$-[[zettel/Funktion/A-S-Messbarkeit|messbar]].

---

$f : \Omega \to \overline{\mathbb{R}}$ ist genau dann $(\mathcal{A}, \overline{\mathcal{L}})$-[[zettel/Funktion/A-S-Messbarkeit|messbar]], falls
- a) $\forall a \in \mathbb{R} : \{ f \gt a \} = \{ \omega \in \Omega, f(\omega) \gt a \}$ = $f^{-1}((a, +\infty]) \in \mathcal{A}$
- b) $\forall a \in \mathbb{R} : \{ f \ge a \} = \{ \omega \in \Omega, f(\omega) \ge a \}$ = $f^{-1}([a, +\infty]) \in \mathcal{A}$
- c) $\forall b \in \mathbb{R} : \{ f \lt b \} = \{ \omega \in \Omega, f(\omega) \lt b \}$ = $f^{-1}([-\infty, b)) \in \mathcal{A}$
- d) $\forall b \in \mathbb{R} : \{ f \le b \} = \{ \omega \in \Omega, f(\omega) \le b \}$ = $f^{-1}([-\infty, b]) \in \mathcal{A}$

a) $\iff$ b) $\iff$ c) $\iff$ d).

Schreibe
- $\{ f \in B \} = f^{-1}(B), B \subseteq R$.