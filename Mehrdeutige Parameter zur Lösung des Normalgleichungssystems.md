Sei $X \in \mathbb{R}^{m \times n}, y \in \mathbb{R}^m$ mit
- $X^TXw = X^Ty$
- Spalten von $X$ linear abhängig $\implies$ $X^TX$ [[Definitheit|positiv semidefinit]] $\implies$ $X^TX$ nicht [[regulär]] bzw. [[singulär]]
- $w$ existiert
- $w$ nicht eindeutig bestimmt
- $w^+ = \arg\min_{w} \| w \|_2^2$
- $X^+ \in \mathbb{R}^{n \times m}$ die [[Pseudoinverse]] von $X$
- $w^+ = X^+y$