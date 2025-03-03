1. Die aus der Analysis bekannte Formel
	
	$$
		\int_0^\infty \frac{\sin x}{x} dx = \frac{\pi}{2}
	$$
	
	bezieht sich auf das uneigentliche Riemann-Integral.
	Zeigen Sie, dass die Funktion $x \mapsto \frac{\sin x}{x}$ nicht $\lambda_{(0, \infty)}$-integrierbar ist.
	
	*Hinweis:* Eine Funktion $f : (0, \infty) \to \mathbb{R}$ ist genau dann $\lambda_{(0, \infty)}$-integrierbar, wenn $|f|$ $\lambda_{(0, \infty)}$-integrierbar ist

^1

2. Beweisen Sie mit dem Satz von der majorisierten Konvergenz:
	
	$$
		\lim_{n \to \infty} \int_0^1 \left[ 1 - \frac{t}{n} \right]^n \log t dt = \int_0^1 e^{-t} \log t dt
	$$

^2

3. Seien $(\Omega, \mathfrak{A}), (R, \mathfrak{S})$ Messräume, $T : (\Omega, \mathfrak{A}) \to (R, \mathfrak{S})$, $\mu$ ein Maß auf $(\Omega, \mathfrak{A})$, sodass das $\mu$-Integral von $\mu \circ T$ existiert.
	Beweisen Sie mit dem Transformationssatz für Integrale
	
	$$
		\int g \circ T d\mu = \int g d\mu^T
	$$
	
	*Hinweis:* Beweis mittels des Prinzips der algebraischen Induktion.

^3