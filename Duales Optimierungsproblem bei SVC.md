---
title: Duales Optimierungsproblem bei SVC
type: definition
---

Minimiere $w$ aus der [[Support-Vector Klassifikation überlappende Cluster|SVC]]

$$
	w = (v, v_0) = \min_{v \ne 0, v_0, \xi} \frac{1}{2} \| v \|_2^2 + C \sum_{i=1}^n \xi_i, \quad \forall i \in \{ 1, \dots, n \} : y_i(v^Tx_i + v_0) \ge 1 - \xi_i
$$

Ersetze das [[restringiertes Optimierungsproblem|restringierte Optimierungsproblem]] durch ein [[Dualität|duales Optimiertungsproblem]] mit
- $w = (v, v_0, \xi) \in X = \mathbb{R}^{m+1+n}$
- $f(w) = \frac{1}{2} \| v \|_2^2 + C \sum_{i=1}^n \xi_i$
- $g_i(w) = \begin{cases} -(y_i(\sum_{j=1}^n v_jx_{ij} + v_0) - 1 + \xi_i), & i \in \{ 1, \dots, n \} \\ -\xi_i & i \in \{ n+1, \dots, 2n \} \end{cases}$

mit der Standardform

$$
	\min_{w \in \mathbb{R}^{m+1+n}} f(w), \quad g(w) \le 0
$$

mit
- $\alpha \ge 0$
- $\beta \ge 0$
- $\lambda = (\alpha, \beta)$

Mit der [[Lagrange-Funktion]]

$$
	L(w, \lambda) = L(v, v_0, \xi, \alpha, \beta) = \frac{1}{2} \| v \|_2^2 + C \sum_{i=1}^n \xi - \sum_{i=1}^n \alpha_i \left( y_i \left( \sum_{j=1}^m v_ix_{ij} + v_ü \right) - 1 + \xi_i \right) = \frac{1}{2} \| v \|_2^2 - \sum_{i=1}^n \alpha_iy_i \sum_{j=1}^m v_jx_{ij} - v_0\sum_{i=1}^n \alpha_iy_i + \sum_{i=1}^n (C - \alpha_i - \beta_i)\xi_i + \sum_{i=1}^n \alpha_i
$$

bzw.

$$
	q(\alpha, \beta) = \inf_{(v, v_0, \xi) \in \mathbb{R}^{m+1+n}} L(v, v_0, \xi, \alpha, \beta)
$$

bzw. durch
- $L$ quadratisch in $v$, [[Funktion lineare affin|linear affin]] in $v_0$ und $\xi$, differenzierbar und [[Funktion konvex|konvex]]
- $q(\alpha, \beta) \gt \infty$, falls
	- $0 = \partial_{v_0} L(v, v_0, \xi, \alpha, \beta) = -\sum_{i=1}^n \alpha_iy_i$
	- $\forall i \in \{ 1, \dots, n \} : \partial_{\xi_i} L(v, v_0 \xi, \alpha, \beta) = C - \alpha_i - \beta_i$

bzw.
- $\forall i \in \{ 1, \dots, n \} : \alpha_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \beta_i \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \alpha_i + \beta_i = C$
- $\sum_{i=1}^n \alpha_iy_i = 0$

vereinfacht sich $L$ zu

$$
	L(v, v_0, \xi, \alpha, \beta) = \frac{1}{2} \| 2 \|_2^2 - \sum_{i=1}^n \alpha_iy_i \sum_{j=1}^m v_jx_{ij} + \sum_{i=1}^n \alpha_i
$$

Sei $\forall k \in \{ 1, \dots, m \} : \hat{v}_k = \sum_{i=1}^n \alpha_iy_ic_{il}$.

Es gilt

$$
	\forall k \in \{ 1, \dots, m \} : 0 = \partial_{v_k} L(\hat{v}, v_0, \xi, \alpha, \beta) = \hat{v}_k - \sum{i=1}^n \alpha_iy_ix_{ik}
$$

Sei
- $Q = (y_ix_i^Tx_ky_k)_{i, k \in \{ 1, \dots, n \}}$
- $e = (1, \dots, 1)^T$

Es gilt

$$
	q(\alpha, \beta) = L(\hat{v}, v_0, \xi, \alpha, \beta) = \begin{cases}
			-\frac{1}{2} \alpha^TQ\alpha + e^T\alpha, & y^T\alpha = 0 \alpha + \beta = Ce \\
			-\infty & \text{sonst}
	\end{cases}
$$

mit den Nebenbedingungen
- $y^T\alpha = 0$
- $\forall i \in \{ 1, \dots, n \} : \alpha_i + \beta_i = c$

 Das optimale $w$ kann durch die Lösung des [[restringiertes Optimierungsproblem|restringiertes Optimierungsproblems]] bestimmt werden mit
- $\beta_i \ge 0$

$$
	\min_{\alpha \ge 0} \left( \frac{1}{2}\alpha^TQ\alpha - e^T\alpha \right)
$$

mit den Nebenbedingungen
- $Q = (y_ix_i^Tx_jy_j)_{i, j \in \{ 1, \dots, n \}}$
- $y^T\alpha = 0$
- $0 \le \alpha \le Ce$