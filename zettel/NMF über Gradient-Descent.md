---
title: NMF über Gradient-Descent
type: definition
---

Sei $V \in \mathbb{R}_+^{m \times n}$ [[Matrix sparse]], $A \star B$ die komponentenweise Multiplikation der Matrizen $A$ und $B$.

Finde eine Lösung der [[Nonnegative-Matrix-Factorisation|NFM]] $V = EF$ über [[Gradient Descent|GD]]  mit
- der [[Loss-Funktion]] $l(E, F)$ definiert als

$$
	l(E, F) = \| V - (E \star E)(F \star F) \|_\text{Fro}^2
$$