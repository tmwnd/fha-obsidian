---
title: restringiertes Optimierungsproblem
type: definition
---

Sei $f : X \to \mathbb{R}$.

Minimiere das [[Optimierungsproblem]]

$$
	\underset{x \in X}{\arg\min} f(x)
$$

mit den Nebenbedingunen
- $g(x) \le 0$
- $h(x) = 0$

---

Sei $f \in C^1(X)$ mit

$$
	L(x, \lambda, \mu) = f(x) + \lambda^Tg(x) + \mu^Th(x)
$$

Falls $x_* \in \arg\min_{x \in X} f(x)$ gilt
- $\exists \lambda_* \ge 0, \mu_* : x_*, \lambda_*, \mu_*$ [[KKT-Bedingungen|KKT-Punkt]]

---

Seien $X$ [[Menge konvex|konvex]], $f$, $g$ [[Funktion konvex|konvex]], $h$ [[Funktion lineare affin|linear affin]]

Es gilt
- Als Regularisierungsbedingung muss nur [[Slater-Bedingung]] erfüllt sein
- $x_*$ [[KKT-Bedingungen|KKT-Punkt]] $\implies$ $x_*$ lokales Minimum $\implies$ $x_*$ globales Minimum

---

Sei $x$ [[Menge konvex|konvex]], $f$ [[Funktion konvex|konvex]]

Es gilt
- $x_* \in X$ ist Minimierer $\iff$ $\forall x \in X : f'(x_*)(x - x_*) \ge 0$

---

Seien $f, g, h \in C^2$.

Falls $x_*, \lambda_*, \mu_*$ ein [[KKT-Bedingungen|KKT-Punkt]] und
- $S = \left\{ s \in \mathbb{R}^2 \mid s \ne 0 \land \begin{pmatrix} \partial_x g(x_*) \\ \partial_x h(x_*) \end{pmatrix}^Ts = 0 \right\}$
- $\forall s \in S : s^T\partial_x^2L (x_*, \lambda_*, \mu_*)s \ge 0$