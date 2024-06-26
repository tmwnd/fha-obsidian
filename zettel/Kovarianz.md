Seien $X_1, X_2$ [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\text{E}[X_1 X_2] \lt \infty \iff \forall i \in \{ 1, 2 \} : \text{E}[X_i^2] \lt \infty$

Die *Kovarianz* ist definiert als

$$
	\text{Cov}[X_1, X_2] := \text{E}[(X_1 - \text{E}[X_1]) \cdot (X_2 - \text{E}[X_2])]
$$

---

Seien $X_1, X_2$ [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\text{E}[X_1 X_2] \lt \infty$

Es gilt aus der [[zettel/Cauchy-Schwarze Ungleichung|Cauchy-Schwarzen Ungeleichung]]

$$
	|\text{Cov}[X_1, X_2]| \le \sqrt{\text{Var}[X_1] \cdot \text{Var}[X_2]}
$$

---

Seien $X_1, X_2$ [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\text{E}[X_1 X_2] \lt \infty$

$X_1, X_2$ heißen *unkorreliert*, falls
- a) $\text{Cov}[X_1, X_2] = 0$
- b) $X_1, X_2$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]]

a) $\iff$ b).

---

Sie $X$ ein $d$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]] mit
- $\forall i \in \{ 1, \dots, d \} : \text{E}[X_i] \lt \infty$ bzw. $\text{E}[|X_i|] \lt \infty$

Die *Kovarianzmatrix* ist definiert als

$$
	\text{Cov}[X] := (\text{Cov}[X_i, X_j])_{1 \le i, j \le d}
$$

Es gilt
- $\text{Cov}[X]$ ist symmetrisch positiv semidefinit
- $\forall A \in \mathbb{R}^{n \times d}, b \in \mathbb{R}^n : \text{Cov}[AX + b] = A\text{Cov}[X]A^T$