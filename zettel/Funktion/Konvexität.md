---
title: Konvexe Funktion
type: property
---

Sei $C \subset \mathbb{R}^d$ [[zettel/Menge/Konvexität|konvex]], $f : C \to \mathbb{R}$ eine [[zettel/Funktion|Funktion]].

$f$ heißt *konvex*, falls
- $\forall x, y \in C, \lambda \in [0, 1] : f((1 - \lambda)x + \lambda y) \le (1 - \lambda)f(x) + \alpha f(y)$

$f$ heißt *strikt konvex*, falls
- $\forall x, y \in C, \lambda \in [0, 1] : f((1 - \lambda)x + \lambda y) \lt (1 - \lambda)f(x) + \alpha f(y)$

---

Es gilt
- Jede Norm $\| \cdot \|$ konvex
- $f$ [[zettel/Funktion/Lineare Affinität|linear affin]] $\implies$ $f$ konvex
- $f$ konvex $\iff$ $f$ differenzierbar $\land$ $\forall x, y \in X : f(y) \ge f(x) + f'(x)(y - x)$
- $f$ konvex und differenzierbar $\iff$ $X$ [[zettel/Menge/Konvexität|konvex]] $\land$ $\forall x, y \in X : (f'(y) - f'(x))(y - x) \ge 0$ bzw. $f'$ monoton wachsend

---

Sei $f$, $g$ konvex.

Es gilt
- $\forall \alpha \ge 0 : \alpha f$ konvex
- $f + g$ konvex
- $\forall A \in \mathbb{R}^{n \times d}, c \in \mathbb{R}^d : f(Ax + b)$ konvex
- $h(x) := \max(f(x), g(x))$ konvex
- $f \circ g$ oft nicht konvex
- $f : X \to \mathbb{R}$ konvex $\iff$ $\text{epi}(f)$ [[zettel/Menge/Konvexität|konvex]]

---

Sei $f : X \to \mathbb{R}$ konvex und differenzierbar, $x \in X$.

Es gilt
- $x$ globales Minimum von $f$ $\iff$ $f'(x) = 0$

und

$$
	\forall x, y \in \text{dom}(f) : f(y) \ge f(x) + f'(x)(y-x)
$$

---

Sei $f : X \to \mathbb{R}$ konvex, $x$ ein lokales Minimum von $f$.

Es gilt
- $x$ ist ein globales Minimum von $f$

---

Sei $f : X \to \mathbb{R}$ strikt konvex, $x$ ein globales Minimum von $f$.

Es gilt
- $x$ ist das einzige globale Minimum von $f$