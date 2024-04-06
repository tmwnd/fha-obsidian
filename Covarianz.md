---
title: Covarianz
type: definition
---

Seien $X_1, X_2$ [[Zufallsvariable|Zufallsvariablen]] mit
- $E[X_1 X_2] \lt \infty \iff \forall i \in \{ 1, 2 \} : E[X_i^2] \lt \infty$

Die *Covarianz* ist mit dem [[Zufallsvariable Erwartungswert|Erwartungswert]] $E$ definiert als

$$
	\text{Cov}(X_1, X_2) = E[(X_1 - E[X_1]) \cdot (X_2 - E[X_2])]
$$

---

Seien $X_1, X_2$ [[Zufallsvariable|Zufallsvariablen]] mit
- $E[X_1 X_2] \lt \infty$

Es gilt aus der [[Cauchy-Schwarze Ungleichung|Cauchy-Schwarzen Ungeleichung]] mit der [[Zufallsvariable Varianz|Varianz]] Var

$$
	|\text{Cov}(X_1, X_2)| \le \sqrt{\text{Var}(X_1) \cdot \text{Var}(X_2)}
$$

---

Seien $X_1, X_2$ [[Zufallsvariable|Zufallsvariablen]] mit
- $E[X_1 X_2] \lt \infty$

$X_1, X_2$ heißen *unkorreliert*, falls
- a) $\text{Cov}(X_1, X_2) = 0$
- b) $X_1, X_2$ [[Zufallsvariable unabhängig|unabhängig]]

a) $\iff$ b).

---

Sie $X$ ein $d$-dimensionaler [[Zufallsvariable|Zufallsvektor]] mit
- $\forall i \in \{ 1, \dots, d \} : E[X_i] \lt \infty$ bzw. $E[|X_i|] \lt \infty$

Die *Kovarianzmatrix* ist definiert als

$$
	\text{Cov}(X) = (\text{Cov}(X_i, X_j))_{1 \le i, j \le d}
$$

Es gilt
- $\text{Cov}(X)$ ist symmetrisch positiv semidefinit
- $\forall A \in \mathbb{R}^{n \times d}, b \in \mathbb{R}^n : \text{Cov}(AX + b) = A\text{Cov}(X)A^T$