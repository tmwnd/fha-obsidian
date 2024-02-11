Sei $\mathcal{A}$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$, $A, B \in \mathcal{A}$, $P$ ein [[Maß|Wahrscheinlichkeitsmaß]].

$A, B$ sind *(stochastisch) unabhängig*, falls
- $P(A \cap B) = P(A) \cdot P(B)$

Es gilt
- $P(A \cap B^C) = P(A) \cdot P(B^C)$
- $A, B^C$ sind unabängig
- $A^C, B^C$ sind unabhängig
- $A^C, B$ sind unabhängig

---

Sei $\mathcal{A}$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$ ,$(A_n)_{n \in \mathbb{N}} \in \mathcal{A}$.

$(A_n)_{n \in \mathbb{N}}$ heißt *(stochastisch) unabhängig*, falls

$$
	\forall I \subset \mathbb{N} : P\left( \bigcap_{i \in I} A_i \right) = \prod_{i \in I} P(A_i)
$$