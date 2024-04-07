---
title: Modellfehler
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $w \in \mathbb{R}^n$, $d$ eine geeignete [[zettel/Metrik|Metrik]], $g$ eine [[zettel/Modellfunktion|Modellfunktion]].

Der *Modellfehler* $l_i : \mathbb{R}^n \to \mathbb{R}_0^+$ an der Stelle $x_i$ ist definiert als

$$
	l_i(w) := d(g(x_i, w), y_i)
$$