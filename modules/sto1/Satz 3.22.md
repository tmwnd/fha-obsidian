---
title: Satz 3.22
type: theorem
---

Sei $X$ ein $d$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]] mit $\lambda^d$-[[zettel/λ-Dichte|Dichte]] $f$, $(M_i)_{i \in \mathbb{I}} \subseteq \mathbb{R}^d$, $T : (\mathbb{R}^d, \mathcal{L}^d) \to (\mathbb{R}^d, \mathcal{L}^d)$  eine geeignete $(\mathcal{L}^d, \mathcal{L}^d)$-[[zettel/Funktion A-S-messbar|messbare]] Transformation, $S$ die Inverse zu $T$ und $\Delta : \mathbb{R}^d \to \mathbb{R}$ die [[zettel/Funktionaldeterminante|Funktionaldeterminante]]  mit
- $f$ verschwindet außerhalb $\bigcup_{i \in I} M_i$
- $I$ abzählbar
- $(M_i)_{i \in \mathbb{I}}$ p. d.
- $\forall i \in I : M_i$ offen
- $\forall i \in I : T_i = T|_{M_i}$ stetig differenzierbar
- $\forall i \in I : \Delta_i(T_i) \ne 0$
- $\forall i \in I : T_i$ injektiv
- $\forall i \in I : S_i : T(M_i) \to M_i$
- $\forall i \in I : S_i$ offen
- $\forall i \in I : S_i$ ist $(\mathcal{L}_{T_i(M_i)}^d, \mathcal{L}_{M_i}^d)$-[[zettel/Funktion A-S-messbar|messbar]]

Die $\lambda$-[[zettel/λ-Dichte|Dichte]] des $d$-dimensionalen [[zettel/Zufallsvariable|Zufallsvektor]] $Y = T \circ X$ ist definiert

$$
	\sum_{i \in I} \frac{f \circ S_i}{|\Delta_i \circ S_i|} I_{T_i(M_i)}
$$