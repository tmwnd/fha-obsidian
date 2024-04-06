---
title: Lineares Ausgleichsproblem
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $w \in \mathbb{R}^n$, $g$ eine [[Modellfunktion]] mit
- $g$ [[Funktion lineare affin|linear affin]]
- $l(w)$ die [[Loss-Funktion]] des [[Least-Square Problem|Least-Square Problems]]

Es gilt bzgl. des [[Residuenvektor|Residuenvektors]]

$$
	L(w) = \begin{pmatrix}
		g(x_1, w) - y_1 \\
		\vdots \\
		g(x_m, w) - y_m
	\end{pmatrix} = \begin{pmatrix}
		G_{x_1}w + c_{x_i} - y_1 \\
		\vdots \\
		G_{x_m}w + c_{x_m} - y_m
	\end{pmatrix} = \underbrace{\begin{pmatrix}
		G_{x_1} \\
		\vdots \\
		G_{x_m}
	\end{pmatrix}}_A w - \underbrace{\begin{pmatrix}
		y_1 - c_{x_1} \\
		\vdots \\
		y_m - c_{x_m}
	\end{pmatrix}}_b = Aw - b
$$

und bzgl. der [[Loss-Funktion]]

$$
	\begin{aligned}
	l(w) & = \frac{1}{2m} \| Aw - b \|_2^2 \\
	l'(w) & = \frac{1}{m} A^T (Aw - b) \\
	l''(w) & = \frac{1}{m} A^TA
	\end{aligned}
$$

und
- $l$ [[Funktion konvex|konvex]] $\implies$ jedes lokale Minimum ist ein globales Minimum
- $l'(w) = 0 \iff A^TAw = A^Tb$
- $l''(w)$ [[Matrix definit|positiv semidefinit]] $\implies$ $w$ ist ein lokales Minimum

Das zu lösende Normalgleichungssystem ist
- $\underbrace{w^* = \arg\min_{w \in \mathbb{R}^n} l(w)}_\text{numerisches Optimierungsproblem} \equiv \underbrace{A^TAw = A^Tb}_\text{linesares Gleichungssystem}$^[$w$ nicht eindeutig, da $g$ mehrere globale Minima enthalten kann]