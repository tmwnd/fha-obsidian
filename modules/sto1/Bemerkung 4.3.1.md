---
title: Bemerkung 4.3.1
type: TODO
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]], $\omega \in \Omega$, $n \in \mathbb{N}$, $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $X : \Omega \to R$ eine [[zettel/Funktion|Funktion]] mit
- $R = \prod_{i=1}^n R_i$
- $\mathscr{S} = \bigotimes_{i=1}^n \mathscr{S}_i$ eine Produkt-$\sigma$-[[zettel/Produkt-σ-Algebra|Algebra]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$
- $(x_1, \dots, x_n) \in R$
- $\forall i \in \{ 1, \dots, n \} : \pi_i : R \to R_i$ mit
	- $\pi_i(x_1, \dots, x_{i-1}, x_i, x_{i+1}, x_n) = x_i$
- $X = (X_1, \dots, X_n)$
- $X(\omega) = (X_1(\omega), \dots, X_n(\omega))$
- $\forall i \in \{ 1, \dots, n \} : \Omega \to R_i$ mit
	- $X_i = \pi_i \circ X$

Es gilt

$$
	\mathscr{S} = \sigma\left( \bigcup_{i=1}^n \pi_i^{-1}(\mathscr{S_i}) \right)
$$

$X$ ist eine [[zettel/Zufallsvariable|Zufallsvariable]], falls
- a) $X$ $(\mathcal{A}, \mathscr{S})$-[[zettel/Funktion/A-S-Messbarkeit|messbar]] ist
- b) $\forall i \in \{ 1, \dots, n \} : X_i$ $(\mathcal{A}, \mathscr{S})$-[[zettel/Funktion/A-S-Messbarkeit|messbar]] ist

a) $\iff$ b).