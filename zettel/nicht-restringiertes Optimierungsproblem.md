---
title: nicht-restringiertes Optimierungsproblem
type: definition
---

Sei $f : \mathbb{R}^d \to \mathbb{R}$.

Minimiere das [[zettel/Optimierungsproblem|Optimierungsproblem]]

$$
	x_* \in \underset{x \in \mathbb{R}^d}{\arg\min} f(x) \ne \emptyset
$$

---

Sei $f \in C^1(\mathbb{R}^d)$.

Falls $x_* \in \arg\min_{x \in \mathbb{R^d}} f(x)$ gilt
- $f'(x_*) = 0$

---

Sei $f \in C^2(\mathbb{R}^d)$.

Falls $x_* \in \arg\min_{x \in \mathbb{R^d}} f(x)$ gilt
- $f'(x_*) = 0$
- $f''(x_*)$ ist [[zettel/Matrix/Definitheit|positiv semidefinit]]

---

Sei $f \in C^2(\mathbb{R}^d)$.

Falls $f'(\tilde{x}) = 0 \land f''(\tilde{x})$ [[zettel/Matrix/Definitheit|positiv semidefinit]] gilt
- $\tilde{x} \in \arg\min_{x \in \mathbb{R^d}} f(x)$

Schreibe
- $\tilde{x}$ ist lokales Minimum