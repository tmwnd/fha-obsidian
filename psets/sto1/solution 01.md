![[assignment 01#^1]]

1. $\mathfrak{A}$ ist eine $\sigma$-[[sigma-Algebra|Algebra]], falls
	1. $\Omega \in \mathfrak{A}$
	2. $A \in \mathfrak{A} \implies A^C \in \mathfrak{A}$
	3. $(A_n)_{n \in \mathbb{N}} \in \mathfrak{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathfrak{A}$
	
	Alle Voraussetzungen sind erfüllt, da
	
	1. $\Omega^C = \emptyset$ abzählbar $\implies$ $\Omega \in \mathfrak{A}$
	2. $A \in \mathfrak{A} \implies A$ abzählbar $\lor A^C$ abzählbar $\implies A^C \in \mathfrak{A}$ mit ${A^C}^C = A$
	3.  
		1. $\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $\bigcup_{n \in \mathbb{N}} A_n$ abzählbar
		2. $\exists k \in \mathbb{N} : A_k$  überabzählbar $\implies$ $A_k^C$ abzählbar $\implies$ $( \bigcup_{n \in \mathbb{N}} A_n)^C = \bigcap_{n \in \mathbb{N}} A_n^C$ abzählbar
2. $m$ ist ein [[Maß]], falls $m$ eine $\sigma$-[[Abbildung|additive]] [[Abbildung]] ist.
	$m$ ist eine $\sigma$-[[Abbildung|additive]] [[Abbildung]], falls
	1. $m(\emptyset) = 0$
	2. p. d. $(A_n)_{n \in \mathbb{N}} \in \mathfrak{A} \implies$
	
	$$
		m\left( \bigcup_{n \in \mathbb{N}} A_n \right) = \sum_{n \in \mathbb{N}} m(A_n)
	$$
	
	Alle Voraussetzungen sind erfüllt, da
	1. $\emptyset$ abzählbar $\implies$ $m(\emptyset) = 0$
	2. 
		1. $m(\bigcup_{n=1}^\infty A_n) = 0$ $\implies$ $\bigcup_{n=1}^\infty A_n$ abzählbar $\implies$ $\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $\sum_{n \in \mathbb{N}} m(A_n) = 0$
		2. $m(\bigcup_{n=1}^\infty A_n) = 1$ $\implies$ $(\bigcup_{n=1}^\infty A_n)^C$ abzählbar $\land$ $\exists k \in \mathbb{N} : A_k^C$ abzählbar[^1] $\land$ $\forall l \in \mathbb{N} \setminus \{ k \} : A_l$ abzählbar[^2] $\implies$ $\sum_{n \in \mathbb{N}} m(A_n) \gt 0 \land \sum_{n \in \mathbb{N}} m(A_n) \le 1$ $\implies$ $\sum_{n \in \mathbb{N}} m(A_n) = 1$

---

![[assignment 01#^2]]

---

![[assignment 01#^3]]


[^1]: $\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $m(\bigcup_{n=1}^\infty A_n) = 0 \ne 1$
[^2]: $A_k^C$ abzählbar $\stackrel{\Omega \text{ überabzählbar}}{\implies}$ $A_k$ überabzählbar $\stackrel{A_k, A_l \text{ diskunkt}}{\implies}$ $A_l \subseteq A_k^C$ $\implies$ $A_l$ abzählbar