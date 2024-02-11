1. Es sei $\Omega$ eine nicht abzählbare Menge und
	
	$$
		\mathfrak{A} := \{ A \subseteq \Omega \mid A \text{ abzählbar } \lor A^C \text{ abtzählbar } \}
	$$
	
	1. Zeigen Sie, dass $\mathfrak{A}$ eine $\sigma$-Algebra auf $\Omega$ ist.
	2. Es sei $m : \mathfrak{A} \to [0, 1]$ definiert durch $m(A) = 0$, falls $A$ anzählbar und $m(A) = 1$, falls $A^C$ abzählbar ist.
	   Zeigen Sie, dass $m$ ein Maß ist.

^1

2. Sei $(\Omega, \mathfrak{A}, P)$ ein Wahrscheinlichkeitsraum.
	Zeigen Sie, dass für das Wahrscheinlichkeitsmaß $P$ die folgenden Eigenschaften gelten:
	
	1. Aus $A, B \in \mathfrak{A}$, $A \subseteq B$, folgt $P(A) \le P(B)$. (Isotonie)
	2. Aus $A, B \in \mathfrak{A}$, $A \subseteq B$, folgt $P(A \cap A^C) = P(B) - P(A)$. (Subtraktivität)
	3. Für $A \in \mathfrak{A}$ ist $P(A^C) = 1 - P(A)$
	4. $P(\emptyset) = 0$
	5. Für endlich viele $A_1, \dots, A_n \in \mathfrak{A}$ gilt
	
	$$
		P\left( \bigcup_{k=1}^n A_k \right) = \sum_{k=1}^n (-1)^{k-1} \sum_{1 \le i_1 \lt \dots \lt i_k \le n} P(A_{i_1} \cap \dots \cap A_{i_k}) \quad \text{(Siebformel)}
	$$
	
	6. Für endlich viele $A_1, \dots, A_n \in \mathfrak{A}$ gilt
	
	$$
		P\left( \bigcup_{j=1}^n A_j \right) \le \sum_{j=1}^n P(A_j) \quad \text{(Subadditivität)}
	$$
	
	7. für $A_n \in \mathfrak{A}$, $n \in \mathbb{N}$, gilt
	
	$$
		P\left( \bigcup_{j=1}^\infty A_j \right) \le \sum_{j=1}^\infty P(A_j) \quad \text{(Sub-}\sigma\text{-additivität)}
	$$
	
^2

3. Es sei $\mathfrak{D}$ ein Mengensystem auf der Menge $\Omega$.
	 Zeigen Sie die Implikation (a) $\implies$ (b) der folgenden Aussagen (es gilt sogar die Rückrichtung):
	- (a) $\mathfrak{D}$ ist ein Dynkin-System auf $\Omega$.
	- (b) hat die Eigenschaften:
		1. $\Omega \in \mathfrak{D}$
		2. $A, B \in \mathfrak{D}, B \subseteq A \implies A \cap B^C \in \mathfrak{D}$
		3. $A_1, A_2, \dots \in \mathfrak{D}$ mit $A_n \subseteq A_{n+1}$ für $n \in \mathbb{N}$ $\implies$ $\bigcup_{n=1}^\infty A_n \in \mathfrak{D}$

^3
