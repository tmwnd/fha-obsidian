---
title: Libschitz-stetige Funktion
type: definition
aliase:
  - L-stetige Funktion
---

Sei $f : \mathbb{R}^d \to \mathbb{R}$ eine [[zettel/Funktion|Funktion]].

$f$ heißt *Libschitz-stetig* bzw. *L-stetig*, falls

$$
	\exists L_f \in \mathbb{R}, \forall x, y \in \text{dom}(f) : |f(y) - f(x)| \le L_f \| y - x \|
$$

---

Sei $f : \text{dom}(f) \to \mathbb{R}$ eine [[zettel/Funktion|Funktion]], $X \subseteq \text{dom}(f)$ [[zettel/Menge offen|offen]] und [[zettel/Menge konvex|konvex]].

Es gilt
- $f$ L-stetig $\iff$ $\forall x \in X : \| f'(x) \| \le L_f$