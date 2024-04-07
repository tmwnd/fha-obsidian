---
title: Satz von Eckart-Young-Mirsky
type: theorem
---

Sei $V \in \mathbb{R}_+^{m \times n}$ [[zettel/Matrix sparse|Matrix sparse]], $k \ll \min(m, n)$.

Zerlege $V$, sodass
- $V \approx WH$
- $W \in \mathbb{R}^{m \times k}$
- $H \in \mathbb{R}^{k \times n}$

Minimiere

$$
	\underset{W \in \mathbb{R}^{m \times k}, H \in \mathbb{R}^{k \times n}}{\arg\min} \| V - WH \|
$$

Falls $\| \cdot \|_2$ oder $\| \cdot \|_\text{Fro}$ verwendet wird, gilt
- $W$, $H$ lässt sich über [[zettel/Singulärwertzerlegung|SVD]] erzeugen

Sei $\tilde{U}\tilde{\Sigma}\tilde{V}^T$ die [[zettel/Singulärwertzerlegung|SVD]] von $V$ bzw. $\tilde{U}_k\tilde{\Sigma}_k\tilde{V}_k^T$ die [[zettel/Abgeschnittene Singulärwertzerlegung|TSVD]] von $V$.

Es gilt

$$
	\underset{W \in \mathbb{R}^{m \times k}, H \in \mathbb{R}^{k \times n}}{\arg\min} \| V - WH \|
$$

wird gelöst durch
- $W = \tilde{U}_k\tilde{\Sigma}_k$
- $H = \tilde{V}_k^T$

bzw. durch
- $W = \tilde{U}_k$
- $H = \tilde{\Sigma}_k\tilde{V}_k^T$

---

Nachteile:
- $W$, $H$ nicht eindeutig
- $V$ [[zettel/Matrix sparse|Matrix sparse]], $W$, $H$ oft nicht [[zettel/Matrix sparse|Matrix sparse]]
- $V \in \mathbb{R}$