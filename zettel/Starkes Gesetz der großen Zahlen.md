---
title: Starkes Gesetz der großen Zahlen
type: definition
aliases:
  - Kolmogorow Gesetz
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]]. $(X_n)_{n \in \mathbb{N}}$ reelle, [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] und identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $\mu \in \mathbb{R}$ mit dem [[zettel/Erwartungswert|Erwartungswert]] $E$ und
- $\forall n \in \mathbb{N} : E[X_n]$ existiert und ist endlich
- $\forall n \in \mathbb{N} : E[X_n] = \mu$

Das *starke Gesetz der großen Zahlen* gilt und es folgt $P$-[[zettel/Konvergenz P-fast sicher|f. s.]]

$$
	\frac{1}{n} \sum_{k=1}^n X_k \overset{P\text{-f. s.}}{\longrightarrow} \mu
$$