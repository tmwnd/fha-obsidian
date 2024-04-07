---
title: μ-konvexe Funktion
type: definition
---

Sei $C \subset \mathbb{R}^d$ [[zettel/Menge/Konvexität|konvex]], $f : C \to \mathbb{R}$ eine [[zettel/Funktion|Funktion]].

$f$ heißt *$\mu$-konvex*, falls
- $\exists \mu \gt 0 : g(x) := f(x) - \frac{\mu}{2} \| x \|_2^2$ [[zettel/Funktion/Konvexität|konvex]] ist

---

Sei $f \in C^1$ $\mu$-konvex.

Es gilt

$$
	\forall x, y \in \text{dom}(f) : f(y) \ge f(x) + f'(x)(y - x) + \frac{\mu}{2} \| y - x \|_2^2
$$

und

$$
	\forall x, y \in \text{dom}(f) : (f'(y) - f'(x))(y - x) \ge \mu \| y - x \|_2^2
$$