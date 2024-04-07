---
title: KKT-Bedingungen
type: definition
aliases:
  - Karush-Kuhn-Tucker-Bedingungen
---

Sei $f$ ein [[zettel/restringiertes Optimierungsproblem|restringiertes Optimierungsproblem]] mit den Nebenbedingungen
- $g(x) \le 0$
- $h(x) = 0$

$x_*, \lambda_*, \mu_*$ heißt *KKT-Punkt*, falls
- $\partial_x L(x_*, \lambda_*, \mu_*) = 0$
- $g(x_*) \le 0$
- $h(x_*) = 0$
- $\lambda_* \ge 0$
- $\forall i \in \{ 1, \dots, d \} : \lambda_{*, i}g_i(x_*) = 0$

---

$\hat{v}, \hat{v}_0$ sind optimale Lösungen eines [[zettel/restringiertes Optimierungsproblem|restringiertes Optimierungsproblems]], falls $(\hat{\alpha}_i)_{i \in \{ 1, \dots, n \}} \ge 0$ existiert mit
- $\forall k \in \{ 1, \dots, m \} : \partial_{v_k} L(\hat{v}, \hat{v}_0, \hat{a}) = 0$
- $\forall i \in \{ 1, \dots, n \} : y_i(\hat{v}^Tx_i + \hat{v}_0) - 1 \ge 0$
- $\forall i \in \{ 1, \dots, n \} : \hat{\alpha}_i(y_i(\hat{v}^Tx_i + \hat{v}_0) - 1) = 0$ (Komplementaritätsbedingung)

TODO