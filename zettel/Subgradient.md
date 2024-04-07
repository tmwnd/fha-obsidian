---
title: Subgradient
type: definition
---

Sei $f : X \to \mathbb{R}$ eine [[zettel/Funktion/Numerische Funktion|numerische]] nicht-differenzierbare [[zettel/Funktion/Konvexität|konvexe]] [[zettel/Funktion|Funktion]], $w \in X$.

Der *Subgradient* $\partial f(w)$ an der Stelle $w$ ist definiert als

$$
	\{ d \in X \mid \forall v \in X : f(v) \ge f(w) + \langle d, v - w \rangle_2 \}
$$

Es gilt
- $\forall w \in X : \partial f(w) \ne \emptyset$
- $\partial (f+g)(w) = \partial f(w) + \partial g(w)$
- $|\partial f(w)| = 1$ $\implies$ $f$ differenzierbar in $w$ $\land$ $df(w) = \partial f(w)$
- $w$ ist ein Minimum von $f$, falls $0 \in \partial f(w)$