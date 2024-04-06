---
title: Loss-Funktion
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $w \in \mathbb{R}^n$, $l_i$ der [[Modellfehler]] an der Stelle $x_i$.

Die *Loss-Funktion* $l : \mathbb{R}^n \to \mathbb{R}_0^+$ ist definiert als

$$
	l(w) := \frac{1}{m} \sum_{i=1}^m l_i(w)
$$