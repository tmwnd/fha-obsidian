Sei $f : \text{dom}(f) \to \mathbb{R}$, $X \subseteq \text{dom}(f)$.

$f$ heißt *L-glatt* auf $X$, falls

$$
	\exists L \ge 0, \forall x, y \in X : f(y) \le f(x) + f'(x)(y-x) + \frac{1}{2} L \| y - x \|_2^2
$$

---

Es gilt
- $f'$ [[Libschitz-Stetigkeit|L-stetig]] $\implies$ $f$ L-glatt

Falls $f \in C^1$ [[Konvexe Funktion|konvex]], $\text{dom}(f) = \mathbb{R}^d$ und $\exists x_* \in \text{dom}(f) : f(x_*) = \inf_x f(x)$ gilt
- $f'$ [[Libschitz-Stetigkeit|L-stetig]] $\iff$ $f$ L-glatt

---

Sei $f : \mathbb{R}^d \to \mathbb{R}$ [[Konvexe Funktion|konvex]] und differenziebar, $\exists x_* \in \text{dom}(f) : f(x_*) = \inf_x f(x)$.

Falls $f$ L-glatt mit $L$ gilt
- $f'$ ist [[Libschitz-Stetigkeit|L-stetig]]

und

$$
	\frac{1}{2L} \| f'(x) \|_2^2 \le f(x) - f(x_*) \le \frac{L}{2} \| x - x_* \|_2^2
$$

---

Sei $f$ L-glatt, $0 \lt \gamma \lt \frac{2}{L}$, $(f_t)_{t \in \mathbb{N}}$.

Es gilt
- $f_t$ fällt monoton

---

Sei $f$ L-glatt

Es gilt
- $\forall \mu \gt 0 : f_R(x) = f(x) + \mu \| x \|_2^2$ $\mu$-[[mu-konvexe Funktion|konvex]]