---
title: Randverteilung
type: definition
---

Sei $n \in \mathbb{N}$, $((X_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable|Zufallsvariablen]], $1 \le k \lt n$, $1 \le i_1 \lt \dots \lt i_k \le n$ mit
- $X = (X_1, \dots, X_n)$

Die *k-dimensionale Randverteilung* von $X$ ist definiert als [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von

$$
	(X_{i_1}, \dots, X_{i_k})
$$

---

Sei $n \in \mathbb{N}$, $((X_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable|Zufallsvariablen]], $1 \le k \lt n$ mit
- $X = (X_1, \dots, X_n)$
- $\forall i \in \{ 1, \dots, n \} : \pi_i$ ist eine Projektion auf $X_i$
- $\forall i \in \{ 1, \dots, n \} : A_i = \pi_i \circ X_i$

Die *k-te Randverteilung* von $X$ ist definiert als [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von

$$
	(X_1, \dots, X_{k-1}, \pi_k \circ X_k, X_{k+1}, \dots, X_n)
$$

Es gilt

$$
	P_{X_k}(A_k) = P_X(X_1, \dots, X_{k-1}, A_k, X_{k+1}, \dots, X_n)
$$