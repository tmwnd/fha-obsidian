---
title: NMF über Scikit-Learn
type: definition
---

Sei $V \in \mathbb{R}_+^{m \times n}$ [[zettel/Matrix sparse|Matrix sparse]], $\alpha, \gamma \ge 0$.

Finde eine Lösung der [[zettel/Nonnegative-Matrix-Factorisation|NFM]] $V = WH$ über das Minimum

$$
	\underset{W \in \mathbb{R}^{m \times k}, H \in \mathbb{R}^{k \times n}}{\arg\min} \left( \frac{1}{2} \| V - WH \|_\text{Fro}^2 + \alpha\gamma \left( \sum_{i,j} |w_{ij}| + \sum_{i,j} |h_{ij}| \right) + \frac{1}{2}\alpha(1 - \gamma)\left( \| W \|_\text{Fro}^2 + \| H \|_\text{Fro}^2 \right)\right)
$$