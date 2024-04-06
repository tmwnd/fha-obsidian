---
type: assignment
---

1. Es sei $X$ eine reelle Zufallsvariable mit der Verteilungsfunktion $F$, $u : [a, b] \to \mathbb{R}$ sei stetig differenzierbar.
	Zeigen Sie mit Hilfe des Satzes von Fubini:
	
	$$
		\int_{(a, b]} u dP^X = u(b)F(b) - u(a)F(a) - \int_a^b u'(x)F(x) dx
	$$

^1

2. Zeigen Sie mit Hilfe des Satzes von Fubini, dass für reelle unabhängige Zufallsvariablen $X, Y$ mit den Verteilungsfunktionen $F, G$ gilt:
	
	$$
		E(|X - Y|) = \int_{-\infty}^{+\infty} (1 - F(X))G(x) dx + \int_{-\infty}^{+\infty} (1 - G(X))F(x) dx
	$$

^2

3. Die Zufallsvariablen $X$ und $Y$ seien unabhängig und exponentialverteilt mit Parameter $\lambda \gt 0$.
	Es seien
	
	$$
		V := X + Y
	$$
	
	$$
		W := \frac{X}{X + Y}
	$$
	
	- a) Bestimmen Sie eine gemeinsame Dichte von $V$ und $W$ mit Hilfe der Transformationsformel für Wahrscheinlichkeiten
	- b) Bestimmen Sie die Verteilungen von $V$ und $W$ unter Verwendung von Teil a)

^3

4. Geben Sie Maßräume $(\Omega_i, \mathfrak{A}_i, \mu_i)$, $i = 1, 2$, und eine nicht-negative Funktion $F : (\Omega_1 \times \Omega_2, \mathfrak{A}_1 \otimes \mathfrak{A}_2) \to (\mathbb{R}, \mathfrak{B})$ an, für die
	
	$$
		\int\left(\int f_{\omega_1}(\omega_2) d\mu_2(\omega_2) \right) d\mu_1(\omega_1) \ne \int\left(\int f_{\omega_2}(\omega_1) d\mu_1(\omega_1) \right) d\mu_2(\omega_2)
	$$
	
	ist.

^4