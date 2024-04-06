---
title: Score-Wert
type: definition
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, m \}}$ Daten-Paare, $g$ eine [[Modellfunktion]] mit
- $\forall i \in \{ 1, \dots, m \} : \hat{y}_i = g(x_i, w)$
- $\overline{y} = \frac{1}{n} \sum_{i=1}^m \hat{y}_i$
- $u = \sum_{i=1}^m (y_i - \hat{y}_i)^2$
- $v = \sum_{i=1}^m (y_i - \overline{y}_i)^2$

Der *Score-Wert* $R^2 \in [0, 1]$ ist definiert als

$$
	R^2 = 1 - \frac{u}{v}
$$