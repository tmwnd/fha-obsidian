---
title: μ-Integrierbarkeit
type: definition
---

Sei $f \in \mathcal{M}$ eine [[zettel/Funktion messbar|messbare]] [[zettel/Funktion|Funktion]].

$f$ hat ein *existierendes* $\mu$-[[zettel/μ-Integral|Integral]], falls
- $\int f^+ d\mu \lt \infty$ oder
- $\int f^- d\mu \lt \infty$

Das $\mu$-[[zettel/μ-Integral|Integral]] auf $f$ ist definiert als

$$
	\int f d\mu = \int f^+ d\mu - \int f^- d\mu
$$

Es gilt
- $|\int f d\mu| \le \int |f| d\mu$

---

Sei $f \in \mathcal{M}$ eine [[zettel/Funktion messbar|messbare]] [[zettel/Funktion|Funktion]].

$f$ heißt *$\mu$-integrierbar*, falls
- $\int f^+ d\mu \lt \infty$ und
- $\int f^- d\mu \lt \infty$

Das $\mu$-[[zettel/μ-Integral|Integral]] auf $f$ ist definiert als

$$
	\int f d\mu = \int f^+ d\mu - \int f^- d\mu
$$

---

Sei $f \in \mathcal{M}$ eine [[zettel/Funktion messbar|messbare]] [[zettel/Funktion|Funktion]].

Es gilt
- $f$ $\mu$-integrierbar $\iff$ $|f|$ $\mu$-integrierbar.

---

Sie $f, g \in \mathcal{M}$ [[zettel/Funktion messbar|messbare]] [[zettel/Funktion|Funktionen]] mit
- $|f| \le |g|$

Es gilt
- $g$ $\mu$-integrierbar $\implies$ $f$ $\mu$-integrierbar