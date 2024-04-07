---
title: Support-Vector Klassifikation
type: definition
aliases:
  - SVC
  - Optimal trennende Hyperebene von nicht-überlappenden Clustern
---

Seien $(x_i, y_i)_{i \in \{ 1, \dots, n \}}$ Datenpaare, $w \in \mathbb{R}^{m+1}$, $H(w)$ eine [[zettel/Hyperebene|Hyperebene]], $g(x, w)$ die Funktion aus $H(w)$, $M \in \mathbb{R}$ der Mindestabstand aller Punkte $x_i$ zu $H(w)$ mit
- $\forall i \in \{ 1, \dots, n \} : x_i \in \mathbb{R}^n$
- $\forall i \in \{ 1, \dots, n \} : y_i \in \{ -1, 1 \}$
- $\forall i \in \{ 1, \dots, n \} : y_ig(x_i, w) \ge M \gt 0$

Es gilt
- $\forall i \in \{ 1, \dots, n \} : y_i = \text{sign}(g(x_i, w))$

Bestimme $v \in \mathbb{R}^m$, $v_0 \in \mathbb{R}$ mit
- $w = (v, v_0)$
- $\| v \|_2 = 1$
- $M$ maximal
- $\forall i \in \{ 1, \dots, n \} : y_ig(x_i, w) \ge M \gt 0$

mit

$$
	M = \max_{\| v \|_2 = 1} M(w), \quad \forall i \in \{ 1, \dots, n \} : y_ig(x_i, w) \ge M \gt 0
$$

bzw. durch die Forderung
- $M(w) \| v \|_2 = 1$ bzw. $M(w) = \frac{1}{\| v \|_2}$

$$
	w = (v, v_0) = \max_{v \ne 0, v_0} \frac{1}{\| v \|_2^2}, \quad \forall i \in \{ 1, \dots, n \} : y_i(v^Tx_i + v_0) \ge 1
$$

bzw. durch
- $\max \frac{1}{\| v \|_2} \equiv \min \frac{1}{2} \| v \|_2^2$

$$
	w = (v, v_0) = \min_{v \ne 0, v_0} \frac{1}{2} \| v \|_2^2, \quad \forall i \in \{ 1, \dots, n \} : y_i(v^Tx_i + v_0) - 1 \ge 0
$$

Das optimale $\hat{w}$ kann durch die Lösung des [[zettel/restringiertes Optimierungsproblem|restringiertes Optimierungsproblems]] $L(v, v_0, \alpha)$ über [[zettel/KKT-Bedingungen|KKT]] bestimmt werden.

$$
	L(v, v_0, \alpha) = \frac{1}{2} \| v \|_2^2 - \sum_{i=1}^n \alpha_i(y_i(v^Tx_i + v_0) - 1) = \frac{1}{2} \sum_{i=1}^n v_i^2 - \sum_{i=1}^n \alpha_i\left(y_i\left( \sum_{j=1}^m v_kx_{ij} + v_0 \right) - 1 \right)
$$

mit
- $\forall i \in \{ 1, \dots, n \} : \alpha_i \in \mathbb{R}$

Es gilt
- $\partial_{v_0} L(v, v_0, \alpha) = - \sum_{i=1}^n \alpha_iy_i$
- $\forall k \in \{ 1, \dots, m \} : \partial_{v_k} L(v, v_0, \alpha) = v_k - \sum_{i=1}^n \alpha_iy_ix_{ik}$

Für optimale Parameter $\hat{v}$, $\hat{v}_0$ muss also gelten
- $0 = \sum_{i=1}^n \hat{\alpha}_iy_i$
- $\hat{v} = \sum_{i=1}^n \hat{\alpha}_iy_ix_i$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : y_i(\hat{v}^Tx_i + \hat{v}_0) \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}(y_i(\hat{v}^Tx_i + \hat{v}_0) - 1) = 0$

und
- $\hat{v}$ ist eine Linearkombination der Produkte $y_ix_i$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}_i = 0$ $\implies$ $x_i$, $y_i$ hat keinen Einfluss auf $\hat{v}$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}_i \gt 0$ $\implies$ $x_i$, $y_i$ heißt *Stützpunkt* bzw. *Support-Punkt* von $H(\hat{v})$
- $\hat{v} \ne 0 \implies \exists \hat{i} \in \{ 1, \dots, n \} : \hat{\alpha}_\hat{i} \ne 0$ bzw.

$$
	y_\hat{i}(\hat{v}^Tx_\hat{i} + \hat{v}_0) - 1 = 0 \iff \hat{v}_0 = \frac{1}{y_\hat{i}} - \hat{v}^Tx_\hat{i} = y_\hat{i} - \hat{v}^Tx_\hat{i}
$$

Sei
- $\hat{v} = \sum_{\hat{\alpha}_i \gt 0} \hat{\alpha}y_ix_i$
- $\hat{f}(x) = \hat{v}^Tx + y_\hat{i} - \hat{v}^Tx_\hat{i} = y_\hat{i} + \hat{v}^T(x - x_\hat{i}) = \hat{v}^Tx + \hat{v}_0$

Es gilt

$$
	\forall i \in \{ 1, \dots, n \} : y_i = \text{sign}(\hat{f}(x_i))
$$