---
title: Cholesky-Zerlegung
type: definition
---

Sei $X = \begin{pmatrix} 1 & x_1 \\ \vdots & \vdots \\ 1 & x_m \end{pmatrix}$, $w = \begin{pmatrix} w_1 \\ w_2 \end{pmatrix}$, $y = \begin{pmatrix} y_1 \\ \vdots \\ y_m \end{pmatrix}$ mit
- $\underbrace{X^TX}_Aw = \underbrace{X^Ty}_b$
- $A$ ist [[Matrix symmetrisch positiv definit|spd]]

Zerlege $A$, sodass
- $A = L^TL$
- $L^Tz = b$
- $Lw = z$
- $L$ ist eine [[Dreiecksmatrix|obere Dreiecksmatrix]]

---

Nachteile:
- Die Komplexität zur Berechnung von $X^TX$ mit $X \in \mathbb{R}^{m \times n}$ ist $\mathcal{O}(mn^2)$
- Die Komplexität der Zerlegung von $A$ ist $\mathcal{O}(n^3)$
- Die [[Kondition]] von $A$ ist $\kappa(A) = \kappa(X)^2$
- $X$ möglicherweise [[Matrix sparse]], $A$ oft nicht [[Matrix sparse]]
- $A$ möglicherweise [[Matrix sparse]], $L$ nicht [[Matrix sparse]]