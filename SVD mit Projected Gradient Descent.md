---
title: SVD mit Projected Gradient Descent
type: definition
---

Sei $X \in \mathbb{R}^{m \times n}$ mit
- $f(v) = \| Xv \|_2^2$
- $f(v_k) = \sigma_1^2$
- $v_1 = \arg\max_{\| v \|_2^2 = 1} f(v) = \arg\max_{\| v \|_2^2 \le 1} f(v)$ der erste [[Matrix Singulärwert|Singulärwert]]

Die $k$-te Iteration der *Singulärwertzerlegung mit Projected Gradient Descent* ist definiert als
- $V_k$ der $k$-te [[Krylov-Raum-Verfahren|Krylov-Raum]]
- $\hat{v}_k$ der $k$-te vom [[Gradient Descent|GD]] erzeugte [[Matrix Singulärwert|Singulärwert]]
- $v_k = \frac{\hat{v}_k - V_k \hat{v}_k}{\| \hat{v}_k - V_k \hat{v}_k \|_2}$ der $k$-te [[Matrix Singulärwert|Singulärwert]]