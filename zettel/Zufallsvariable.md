---
title: Zufallsvariable
type: definition
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $(R, \mathscr{S})$ ein [[zettel/Messraum|Messraum]].

Eine $(\mathcal{A}, \mathscr{S})$-[[zettel/Funktion/A-S-Messbarkeit|messbare]] [[zettel/Funktion|Funktion]] $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ heißt *Zufallsvariable*.

---

$F(X)$ heißt [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von $X : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$, falls
- $X$ eine reelwertige Zufallsvariable ist

Sei $x \in \mathbb{R}$.

$F(X)$ ist definiert als

$$
	F(X) = P(X \le x) = P(X \in (-\infty, x))
$$

---

Seien $(X_i)_{i \in \{ 1, \dots, d \}}$ reelle Zufallsvariablen mit
- $\forall i \in \{ 1, \dots, d \} : X_i : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathcal{L})$
- $X = (X_1, \dots, X_d)$ heißt *Zufallsvektor*

Sei $(x_i)_{i \in \{ 1, \dots, d \}} \in \mathbb{R}$.

Es gilt

$$
	X^{-1}\left( \prod_{i=1}^d (-\infty, x_i] \right) = \bigcap_{i=1}^d X_i^{-1}((-\infty, x_i])

$$

mit der [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von $X$

$$
	F(x_1, \dots, x_d) = P\left( X^{-1}\left( \prod_{i=1}^d (-\infty, x_i] \right)\right) = P(X_1 \le x_1, \dots, X_d \le X_d)
$$

---

Sei $X : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ eine Zufallsvariable, $B \in \mathcal{A}$.

Das [[zettel/Bildmaß|Bildmaß]] $P^X$ heißt *Verteilung* von $X$.

Schreibe
- $P^X(B) = P(X \in B)$