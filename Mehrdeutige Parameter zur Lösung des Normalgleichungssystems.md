Sei $X \in \mathbb{R}^{m \times n}, y \in \mathbb{R}^m$ mit
- $X^TXw = X^Ty$
- Spaltenvektoren von $X$ linear abhängig $\implies$ $X^TX$ [[Definitheit|positiv semidefinit]] $\implies$ $X^TX$ nicht [[regulär]] bzw. [[singulär]]
- $U\Sigma V$ die [[Singulärwertzerlegung, SVD|SVD]] von $X$
- $w$ existiert
- $w$ nicht eindeutig bestimmt
- $X^+ \in \mathbb{R}^{n \times m}$ die [[Pseudoinverse]] von $X$

Suche
- $w^+ = \arg\min_{w} \| w \|_2^2$

Es gilt

$$
	\| Xw - y \|_2^2 = \| U\Sigma V^Tw - y \|_2^2 = \| \Sigma \underbrace{V^Tw}_\hat{w} - \underbrace{U^Ty}_\hat{y} \| = \| \Sigma\hat{w} - \hat{y} \|_2^2
$$

und
- $\hat{w}^+ = \begin{pmatrix} \frac{\hat{y}_1}{\sigma_1}, \dots, \frac{\hat{y}_r}{\sigma_r}, 0, \dots, 0 \end{pmatrix}^T$
- $\hat{y} = U^Ty$
- $w^+ = V\hat{w}^+ = V\Sigma^+U^Ty = X^+y$