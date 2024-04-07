---
title: Verteilungsfunktion
type: definition
---

Eine [[zettel/Funktion|Funktion]] $F : \mathbb{R} \to \mathbb{R}$ heißt *Verteilungsfunktion* gemäß des korerspondierenden [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaßes]] $P$, falls
- $F$ monoton wachend ist
- $F$ rechtsseitig stetig ist

$$
	\forall (x_n)_{n \in \mathbb{N}} \subseteq \mathbb{R}, x_n \downarrow x : \lim_{n \to \infty} F(x_n) = F_x
$$

- $F$ besitzt linksseitige Limiten

$$
	\forall (x_n)_{n \in \mathbb{N}} \subseteq \mathbb{R}, x_n \uparrow x : \exists \lim_{n \to \infty} F(x_n)
$$

- $\lim_{x \to -\infty} F(x) = 0$
- $\lim_{x \to +\infty} F(x) = 1$