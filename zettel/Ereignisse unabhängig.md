---
title: Unabhängige Ereignisse
type: definition
---

Sei $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $A, B \in \mathcal{A}$, $P$ ein [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]].

$A, B$ sind *(stochastisch) unabhängig*, falls
- $P(A \cap B) = P(A) \cdot P(B)$

Es gilt
- $P(A \cap B^\complement) = P(A) \cdot P(B^\complement)$
- $A, B^\complement$ sind unabängig
- $A^\complement, B^\complement$ sind unabhängig
- $A^\complement, B$ sind unabhängig

---

Sei $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$ ,$(A_n)_{n \in \mathbb{N}} \in \mathcal{A}$.

$(A_n)_{n \in \mathbb{N}}$ heißt *(stochastisch) unabhängig*, falls

$$
	\forall I \subset \mathbb{N} : P\left( \bigcap_{i \in I} A_i \right) = \prod_{i \in I} P(A_i)
$$