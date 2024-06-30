Sei $f$ ein [[zettel/restringiertes Optimierungsproblem|restringiertes Optimierungsproblem]] mit den Nebenbedingungen
- $g(x) \le 0$
- $h(x) = 0$

mit der [[zettel/Lagrange-Funktion|Lagrange-Funktion]]

$$
	L(x, \lambda, \mu) = f(x) + \lambda^Tg(x) + \mu^Th(x)
$$

Sei $q$ eine duale [[zettel/Funktion|Funktion]] definiert als

$$
	q(\lambda, \mu) := \inf_{x \in X} L(x, \lambda, \mu)
$$

mit dem Definitionsbereich

$$
	\text{dom}_{q} = \{ (\lambda, \mu) \mid \lambda \ge 0 \land q(\lambda, \mu) \gt -\infty \}
$$

Maximiere das [[zettel/Optimierungsproblem|Optimierungsproblem]]

$$
	\max_{\lambda \ge 0, \mu} q(\lambda, \mu)
$$

mit dem Definitionsbereich für $x$

$$
	R_p = \{ x \in X \mid g(x) \le 0 \land h(x) = 0 \}
$$

Es gilt
- $\text{dom}_q$ ist [[zettel/Funktion/Konvexität|konvex]]
- $-q$ ist [[zettel/Funktion/Konvexität|konvex]]
- $\sup_{\text{dom}_q} q(\lambda, \mu) \le \inf_{R_p} f(x)$

Sei $x_*$ eine Lösung von $\inf_{R_p} f(x)$, $\lambda_*, \mu_*$ die Lösung von $\sup_{\text{dom}_q} q(\lambda, \mu)$.

Falls $f(x_*) - q(\lambda_*, \mu_*) \ge 0$
- Bezeichne die Differenz $f(x_*) - q(\lambda_*, \mu_*)$ als *Dualitäts-Lücke*

Falls $f(x_*) - q(\lambda_*, \mu_*) = 0$ gilt
- *starke Dualität*

Falls $f$, $g$ [[zettel/Funktion/Konvexität|konvex]], $h$ [[zettel/Funktion/Lineare Affinität|linear affin]] gilt
- *starke Dualität*

---

Duale Probleme lösen für $f_* = f(x_*)$.

---

Sei $\overline{x}$ eine Näherung für $x_*$, $\overline{\lambda}$, $\overline{\mu}$ geeignet mit
- geltender starker Dualität

Die Fehlerindikator für $\overline{x}$ ist definiert als

$$
	f(\overline{x}) - q(\overline{\lambda}, \overline{\mu})
$$