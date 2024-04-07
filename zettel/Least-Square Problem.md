---
title: Least-Square Problem
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Datenpaare, $w \in \mathbb{R}^n$, $g$ eine [[zettel/Modellfunktion|Modellfunktion]], $L$ der [[zettel/Residuenvektor|Residuenvektor]] mit
- $l_i := \frac{1}{2} \| g(x_i, w) - y_i \|_2^2$ der [[zettel/Modellfehler|Modellfehler]] in $x_i$ bzw.
- $l := \frac{1}{2m} \sum_{i=1}^m l_i(w) = \frac{1}{2m} \| L(w) \|_2^2$ die [[zettel/Loss-Funktion|Loss-Funktion]]

Die Berechnung des optimalen Parameters $w^*$ über das [[zettel/nicht-restringiertes Optimierungsproblem|nicht-restringierte Optimierungsproblem]] wird zu einem *Least-Square Problem*.