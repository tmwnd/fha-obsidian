---
title: Lineare Regression
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $w \in \mathbb{R}^n$, $l(w)$ eine [[zettel/Loss-Funktion|Loss-Funktion]], $g(x, w)$ eine [[zettel/Modellfunktion|Modellfunktion]].

Der optimale Parameter $w^*$ wird über das [[zettel/nicht-restringiertes Optimierungsproblem|nicht-restringiertes Optimierungsproblem]] definiert als

$$
	w^* := \underset{w \in \mathbb{R}^n}{\arg\min} \ l(w)
$$

TODO