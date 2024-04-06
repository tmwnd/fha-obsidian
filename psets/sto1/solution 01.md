![[psets/sto1/assignment 01#^1]]

1. $\mathfrak{A}$ ist eine $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$, falls
	1. $\Omega \in \mathfrak{A}$
	2. $A \in \mathfrak{A} \implies A^\complement \in \mathfrak{A}$
	3. $\forall (A_n)_{n \in \mathbb{N}} \in \mathfrak{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathfrak{A}$
	
	Alle Voraussetzungen sind erfüllt, da
	
	1. $\Omega^\complement = \emptyset$ abzählbar $\implies$ $\Omega \in \mathfrak{A}$
	2. $A \in \mathfrak{A} \implies A$ abzählbar $\lor A^\complement$ abzählbar $\implies A^\complement \in \mathfrak{A}$ mit ${A^\complement}^\complement = A$
	3.  
		1. $\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $\bigcup_{n \in \mathbb{N}} A_n$ abzählbar
		2. $\exists k \in \mathbb{N} : A_k$  überabzählbar $\implies$ $A_k^\complement$ abzählbar $\implies$ $( \bigcup_{n \in \mathbb{N}} A_n)^\complement = \bigcap_{n \in \mathbb{N}} A_n^\complement$ abzählbar
2. $m$ ist ein [[Maß]], falls $m$ eine $\sigma$-[[Funktion sigma-additiv|additive]] [[Funktion]] ist.
	$m$ ist eine $\sigma$-[[Funktion sigma-additiv|additive]] [[Funktion]], falls
	1. $m(\emptyset) = 0$
	2. p. d. $(A_n)_{n \in \mathbb{N}} \in \mathfrak{A} \implies$
	
	$$
		m\left( \bigcup_{n \in \mathbb{N}} A_n \right) = \sum_{n \in \mathbb{N}} m(A_n)
	$$
	
	Alle Voraussetzungen sind erfüllt, da
	1. $\emptyset$ abzählbar $\implies$ $m(\emptyset) = 0$
	2. 
		1. $m(\bigcup_{n=1}^\infty A_n) = 0$ $\implies$ $\bigcup_{n=1}^\infty A_n$ abzählbar $\implies$ $\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $\sum_{n \in \mathbb{N}} m(A_n) = 0$
		2. $m(\bigcup_{n=1}^\infty A_n) = 1$ $\implies$ $(\bigcup_{n=1}^\infty A_n)^\complement$ abzählbar $\land$ $\exists k \in \mathbb{N} : A_k^\complement$ abzählbar^[$\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $m(\bigcup_{n=1}^\infty A_n) = 0 \ne 1$] $\land$ $\forall l \in \mathbb{N} \setminus \{ k \} : A_l$ abzählbar^[$A_k^\complement$ abzählbar $\overset{\Omega \text{ überabzählbar}}{\implies}$ $A_k$ überabzählbar $\overset{A_k, A_l \text{ diskunkt}}{\implies}$ $A_l \subseteq A_k^\complement$ $\implies$ $A_l$ abzählbar] $\implies$ $\sum_{n \in \mathbb{N}} m(A_n) \gt 0 \land \sum_{n \in \mathbb{N}} m(A_n) \le 1$ $\implies$ $\sum_{n \in \mathbb{N}} m(A_n) = 1$

---

![[psets/sto1/assignment 01#^2]]

---

![[psets/sto1/assignment 01#^3]]