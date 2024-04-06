---
title: Dynkin-System
type: definition
---

$\mathcal{D} \subseteq \mathcal{P}(\Omega)$ heißt *Dynkin-System* auf $\Omega$, falls
- $\Omega \in \mathcal{D}$
- $A \in \mathcal{D} \implies A^\complement \in \mathcal{D}$
- $\forall (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{D} : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{D}$

---

Für eine beliebige Teilmenge $\mathcal{E} \subseteq \mathcal{P}(\Omega)$ ist

$$
	\delta(\mathcal{E}) = \bigcap_{\mathcal{D} \text{ Dynkin-System auf } \Omega, \ \mathcal{E} \in \mathcal{D}} \mathcal{D}
$$

das von $\mathcal{E}$ erzeugte Dynkin-System.