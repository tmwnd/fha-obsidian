---
title: unabhängige Zufallsvariablen
type: definition
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $n \in \mathbb{N}$, $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable|Zufallsvariablen]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ mit
- $\mathscr{S} = \bigotimes_{i=1}^n \mathscr{S}_i$ eine Produkt-$\sigma$-[[zettel/Produkt-σ-Algebra|Algebra]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$

$(X_i)_{i \in \{ 1, \dots, n \}}$ heißen *(stochastisch) unabhängig*, falls
- $P^{(X_1, \dots, X_n)} = P^{X_1} \otimes \dots \otimes P^{X_n}$

Es gilt

$$
	\forall i \in \{ 1, \dots, n \}, B_i \in \mathscr{S}_i : P\left( (X_1, \dots, X_n) \in \prod_{i=1}^n B_i \right) = P(X_1 \in B_1) \cdot \dots \cdot P(X_n \in B_n)
$$

mit
- $P\left( (X_1, \dots, X_n) \in \prod_{i=1}^n B_i \right) = P(X_1 \in B_i, \dots, X_n \in B_n)$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $n \in \mathbb{N}$, $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable|Zufallsvariablen]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ mit
- $R = \prod_{i=1}^n R_i$
- $X = (X_1, \dots, X_n)$
- $F$ ist die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von $X$
- $\forall i \in \{ 1, \dots, n \} : F_i$ ist die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von $X_i$

$(X_i)_{i \in \{ 1, \dots, n \}}$ sind unabhängig, falls

$$
	\forall x \in R : F_{(X_1, \dots, X_n)}(x) = \prod_{i=1}^n F_{X_1}(X)
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $n \in \mathbb{N}$, $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable|Zufallsvariablen]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$, $\mu_1, \dots, \mu_n$ $\sigma$-[[zettel/Maß|endliche]] TODO [[zettel/Maß|Maße]] auf $(\mathscr{S})_{i \in \{ 1, \dots, n \}}$, $f_1, \dots, f_n$ nicht-negative [[zettel/Funktion|Funktionen]] mit
- $R = \prod_{i=1}^n R_i$
- $\mathscr{S} = \bigotimes_{i=1}^n \mathscr{S}_i$ eine Produkt-$\sigma$-[[zettel/Produkt-σ-Algebra|Algebra]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$
- $\mu = \bigotimes_{i=1}^n \mu_i$ das [[zettel/Produktmaß|Produktmaß]] von $\mu_1, \dots, \mu_2$
- $\forall i \in \{ 1, \dots, n \} : f_i : (R_i, \mathscr{S}_i) \to (\mathbb{R}, \mathcal{L})$ [[zettel/Funktion messbar|messbar]]
- $\forall i \in \{ 1, \dots, n \} : \int f_i d\mu_1 = 1$
- $(x_1, \dots, x_n) \in R$
- $f : R \to R$ ist definiert als
  
  $$
  f(x_1, \dots, x_n) = \prod_{i=1}^n f_i(x_i)
  $$
  
- $f$ ist $(\mathscr{S}, \mathcal{L})$ [[zettel/Funktion messbar|messbar]]
- $\int f d\mu = 1$

$(X_i)_{i \in \{ 1, \dots, n \}}$ sind unabhängig, falls
- $P^X$ die $\mu$-[[zettel/μ-Dichte|Dichte]] $f$ hat

Es gilt
- $\forall i \in \{ 1, \dots, n \} : x_i$ hat die $\mu$-[[zettel/μ-Dichte|Dichte]] $f_i$
- $X$ hat die $\mu$-[[zettel/μ-Dichte|Dichte]] $f$, falls
	- $\forall i \in \{ 1, \dots, n \} : P^{X_i}$ die $\mu$-[[zettel/μ-Dichte|Dichte]] $\mu_i$ hat

---

Sei $n \in \mathbb{N}$, $(X_i)_{i \in \{ 1, \dots, n \}}$ unabhängige [[zettel/Zufallsvariable|Zufallsvariablen]], $1 \le k \lt  n$, $1 \le i_1 \lt \dots \lt i_k \le n$.

Es gilt
- $(X_i)_{i \in \{ i_1, \dots, i_k \}}$ sind unabhängig

---

Sei $n \in \mathbb{N}$, $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $(X_i)_{i \in \{ 1, \dots, n \}}$ unabhängige [[zettel/Zufallsvariable|Zufallsvariablen]], $g_i : (R_i, \mathscr{S}_i) \to (S_i, \mathcal{T}_i)$ $(\mathscr{S}_i, \mathcal{T}_i)$-[[zettel/Funktion A-S-messbar|messbare]] [[zettel/Funktion|Funktionen]].

Es gilt
- $(g_i \circ X_1), \dots, (g_n \circ X_n)$ sind unabhängig