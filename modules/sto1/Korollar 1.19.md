---
title: Korollar 1.19
type: corollary
---

Sei $F : \mathbb{R}^d \to \mathbb{R}$ eine [[zettel/Funktion|Funktion]] mit
- $\Delta_S F \ge 0$
- $x_n^d \downarrow x^d \implies \lim_{n \to \infty} F(x_n^d) = F(x)$ mit $\forall i \in \{ 1, \dots, d \} : x_n^{(i)} \downarrow x^{(i)}$
- $\forall i \in \{ 1, \dots, d \} : x_1, \dots, x_{i - 1}, x_{i + 1}, \dots, x_d \in \mathbb{R} \implies$

$$
	\lim_{x \to -\infty} F(x_1, \dots, x_{i - 1}, x, x_{i + 1}, \dots, x_d) = 0
$$

Falls $a \in \mathbb{R}$ exisitert mit
- $\lim_{min(x_1, \dots, x_d) \to +\infty} F(x_1, \dots, x_d) = a$

Dann existiert genau ein [[zettel/Maß|Maß]] $\mu$ auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathcal{L}^d$ mit

$$
	\forall (x_1, \dots, x_d) \in \mathbb{R}^d : \mu(S_{(x_1, \dots, x_d)}) = F(x_1, \dots, x_d)
$$

---

Es gilt
- $\mu(\mathbb{R}^d) = a$
- $a = 1$ $\implies$ $\mu$ ist ein [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]], $F$ ist eine [[zettel/Verteilungsfunktion|Verteilungsfunktion]] gemäß des korrespondierenden [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaßes]] $P$.