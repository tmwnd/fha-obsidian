---
title: Konvergenz P-fast sicher
type: definition
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $n \in \mathbb{N}$, $X, (X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable|Zufallsvektoren]] mit
- $\forall n \in \{ 1, \dots, n \} : X_n : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathcal{L}^d)$ [[zettel/Funktion/Messbarkeit|messbar]]

Die Folge $(X_i)_{i \in \{ 1, \dots, n \}}$ *konvergiert $P$-fast sicher* gegen $X$, falls
- $\exists N \in \mathcal{A}$ eine $P$-[[zettel/μ-Nullmenge|Nullmenge]] mit

$$
	\forall \omega \in N^\complement : \lim_{n \to \infty} X_n(\omega) = X(\omega)
$$

Schreibe
- $X_n \to X$ $P$-f. s. oder $X_n \overset{P\text{-f. s.}}{\longrightarrow} X$

---

Seien $X, (X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable|Zufallsvariablen]].

$X_n \overset{P\text{-f. s.}}{\longrightarrow} X$ gilt falls
- $P(\lim_{n \to \infty} X_n = X) = 1$

---

Seien $X, X', (X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable|Zufallsvariablen]].

$X \overset{P\text{-f. s.}}{=} X'$ gilt, falls
- $X_n \overset{P\text{-f. s.}}{\longrightarrow} X$
- $X_n \overset{P\text{-f. s.}}{\longrightarrow} X'$

---

Sei $d, m \in \mathbb{N}$, $X, (X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable|Zufallsvariablen]], $f : \mathbb{R}^d \to \mathbb{R}^m$ $P$-fast sicher stetig.

$f \circ X_n \overset{P\text{-f. s.}}{\longrightarrow} f \circ X$ gilt falls
- $X_n \overset{P\text{-f. s.}}{\longrightarrow} X$

---

Seien $(X_n)_{n \in \mathbb{N}}$ reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit dem [[zettel/Erwartungswert|Erwartungswert]] $E$, der [[zettel/Varianz|Varianz]] $\text{Var}$ und
- $\forall n \in \mathbb{N} : E[X_n]  = 0$
- $\sum_{n=1}^\infty \text{Var}(X_n) \lt \infty$

$\sum_{n=1}^\infty X_k$ konvergiert $P$-f. s. gegen eine reelle [[zettel/Zufallsvariable|Zufallsvariable]]