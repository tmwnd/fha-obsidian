---
title: Lasso-Regularisierung
type: definition
aliases:
  - Tikhonov-Regularisierung mit L1-Strafterm
---

Sei $X \in \mathbb{R}^{m \times n}$, $y \in \mathbb{R}^m$, $w \in \mathbb{R}^n$, $\alpha \gt 0$.

Minimiere

$$
	f(w) = \| Xw - y \|_2^2 + \alpha \| w \|_1
$$

mit

$$
	\partial f(w) = \frac{1}{m} X^T\underbrace{(Xw - y)}_r + \alpha\partial \| w \|_1 = \frac{1}{m} X^Tr + \alpha\partial \| w \|_1
$$

bzw. für die $k$-te Komponente von $\partial f(w)$

$$
	\partial_{w_k} f(w) = \frac{1}{m} \langle x_k, r \rangle_2 + \alpha\underbrace{\partial |w_k|}_d = \frac{1}{m} \langle x_k, r \rangle_2 + \alpha d
$$

mit

$$
	d = \begin{cases}
		-1, & w_k \lt 0 \\
		[-1, 1], & w_k = 0 \\
		1, &  w_k \gt 0
	\end{cases} \implies w_k = \frac{\langle x_k, y_k \rangle_2 - \alpha dm}{\langle x, x \rangle_2}
$$

---

Sei $X \in \mathbb{R}^{m \times n}$, $y \in \mathbb{R}^m$, $w \in \mathbb{R}^n$ ein Löser von $X^TXw = X^Ty$, $\alpha \gt 0$ mit
- $\forall k \in \{ 1, \dots, m \} : \varphi_k = \angle(x_k, r)$

Es gilt
- $\forall k \in \{ 1, \dots, m \} : w_k = 0 \iff |\langle x_k, r \rangle_2| \le \alpha m$ bzw. 

$$
	|\cos(\varphi_k)| = |\frac{\langle x_k, r \rangle_2}{\| x_k \|_2 \| r \|_2}| \le \frac{\alpha m}{\| x_k \|_2 \| r \|_2}
$$