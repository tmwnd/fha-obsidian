Sei $X \in \mathbb{R}^{m \times n}, y \in \mathbb{R}^m$, $w^{(0)} \in \mathbb{R}^n$ mit
- $\underbrace{X^TX}_Aw = \underbrace{X^Ty}_b$
- $A$ ist [[Matrix symmetrisch positiv definit, spd|spd]]
- $s^{(0)} = y - Xw^{(0)}$
- $p^{(0)} = r^{(0)} = X^Ts^{(0)}$

Der $k$-te Schritt von *CGLS* ist definiert als
- $\gamma^{(k)} = \frac{\langle r^{(k)}, r^{(k)} \rangle_2}{\langle Xp^{(k)}, Xp^{(k)} \rangle_2}$
- $w^{(k+1)} = w^{(k)} + \gamma^{(k)}p^{(k)}$
- $s^{(k+1)} = s^{(k)} - \gamma^{(k)}Xp^{(k)}$
- $r^{(k+1)} = X^Ts^{(k+1)}$
- $\beta^{(k)} = \frac{\langle r^{(k+1)}, r^{(k+1)} \rangle_2}{\langle r^{(k)}, r^{(k)} \rangle_2}$
- $p^{(k+1)} = r^{(k+1)} + \beta^{(k)}p^{(k)}$

---

CGLS optimiert [[Conjugate Gradients, CG|CG]] für [[Least-Square Problem|Least-Square Probleme]].