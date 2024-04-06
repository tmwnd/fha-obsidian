---
title: Algebra
type: definition
---

$\mathcal{A} \subseteq \mathcal{P}(\Omega)$ heißt *Algebra* auf $\Omega$, falls
- $\Omega \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
- $A, B \in \mathcal{A} \implies A \cup B \in \mathcal{A}$

---

Für eine beliebige Teilmenge $\mathcal{E} \subseteq \mathcal{P}(\Omega)$ ist

$$
	A(\mathcal{E}) = \bigcap_{\mathcal{A} \text{ Algebra auf } \Omega, \ \mathcal{E} \subseteq \mathcal{A}} \mathcal{A}
$$

die von $\mathcal{E}$ erzeugte Algebra.