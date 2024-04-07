---
title: Krylov-Raum-Verfahren
type: definition
aliases:
  - ARPACK
---

Sei $A \in \mathbb{R}^{m \times n}$ mit
- $U\Sigma V^T$ die [[zettel/Singulärwertzerlegung|SVD]] von $A$

Die $k$-te Iteration der *Krylov Raum Verfahrens* ist definiert als
- $v_k = \sigma_k = \Sigma_{kk}$ der $k$-te [[zettel/Singulärwert|Singulärwert]]
- $V_k = \text{span}(v_1, \dots, v_k) \in \mathbb{R}^{n \times k}$ der $k$-te Krylov-Raum