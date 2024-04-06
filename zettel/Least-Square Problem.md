---
title: Least-Square Problem
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $w \in \mathbb{R}^n$, $g$ eine [[Modellfunktion]], $L$ der [[Residuenvektor]] mit
- $l_i := \frac{1}{2} \| g(x_i, w) - y_i \|_2^2$ der [[Modellfehler]] in $x_i$ bzw.
- $l := \frac{1}{2m} \sum_{i=1}^m l_i(w) = \frac{1}{2m} \| L(w) \|_2^2$ die [[Loss-Funktion]]

Die Berechnung des optimalen Parameters $w^*$ über das [[nicht-restringiertes Optimierungsproblem|nicht-restringierte Optimierungsproblem]] wird zu einem *Least-Square Problem*.