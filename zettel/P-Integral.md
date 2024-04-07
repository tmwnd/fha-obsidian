---
title: P-Integral
type: definition
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]], $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit der $\lambda$-[[zettel/λ-Dichte|Dichte]] $f : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$.

Das *$P$-Integral* ist definiert als

$$
	\int X dP = \int x f(x) dx
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\mathcal{L}$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]], $X : (\Omega, \mathcal{A}) \to (\overline{R}, \overline{\mathcal{L}})$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit der $\lambda$-[[zettel/λ-Dichte|Dichte]] $f : (\mathbb{R}, \mathcal{L}) \to (\mathbb{R}, \mathcal{L})$, $g : (\mathbb{R}, \mathscr{S}) \to (\mathbb{R}, \mathcal{L})$ eine beliebige [[zettel/Funktion|Funktion]],  $A \in \mathscr{S}$.

Wir betrachten die Folgenden Aussagen
- a) $g \circ X$ ist $P$-integrierbar
- b) $g$ ist $P^X$-[[zettel/PX-Integral|integrierbar]]
- c) $g \cdot f$ $\lambda$-[[zettel/λ-Integral|integrierbar]] ist

a) $\iff$ b) $\iff$ c).