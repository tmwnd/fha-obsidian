---
title: Nonnegative-Matrix-Factorisation
type: definition
aliases:
  - NMF
---

Sei $V \in \mathbb{R}_+^{m \times n}$ [[zettel/Matrix sparse|Matrix sparse]], $k \ll \min(m, n)$.

Zerlege $V$, sodass
- $V \approx WH$
- $W = E \star E \in \mathbb{R}^{m \times k}$
- $H = F \star F \in \mathbb{R}^{k \times n}$

Minimiere

$$
	\underset{W \in \mathbb{R}^{m \times k}, H \in \mathbb{R}^{k \times n}}{\arg\min} \| V - WH \|
$$