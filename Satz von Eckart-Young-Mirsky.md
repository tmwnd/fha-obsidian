Sei $V \in \mathbb{R}_+^{m \times n}$ [[sparse]], $k \ll \min(m, n)$.

Zerlege $V$, sodass
- $V \approx WH$
- $W \in \mathbb{R}^{m \times k}$
- $H \in \mathbb{R}^{k \times n}$

Minimiere

$$
	\underset{W \in \mathbb{R}^{m \times k}, H \in \mathbb{R}^{k \times n}}{\arg\min} \| V - WH \|
$$

Falls $\| \cdot \|_2$ oder $\| \cdot \|_\text{Fro}$ verwendet wird, gilt
- $W$, $H$ lässt sich über [[Singulärwertzerlegung, SVD|SVD]] erzeugen

Sei $\tilde{U}\tilde{\Sigma}\tilde{V}^T$ die [[Singulärwertzerlegung, SVD|SVD]] von $V$ bzw. $\tilde{U}_k\tilde{\Sigma}_k\tilde{V}_k^T$ die [[Abgeschnittene Singulärwertzerlegung, TSVD|TSVD]] von $V$.

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
- $V$ [[sparse]], $W$, $H$ oft nicht [[sparse]]
- $V \in \mathbb{R}$