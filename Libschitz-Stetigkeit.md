Sei $f : \mathbb{R}^d \to \mathbb{R}$ eine [[Funktion]].

$f$ heißt *Libschitz-stetig* bzw. *L-stetig*, falls

$$
	\exists L_f \in \mathbb{R}, \forall x, y \in \text{dom}(f) : |f(y) - f(x)| \le L_f \| y - x \|
$$

---

Sei $f : \text{dom}(f) \to \mathbb{R}$ eine [[Funktion]], $X \subseteq \text{dom}(f)$ [[offene Menge|offen]] und [[Konvexe Menge|konvex]].

Es gilt
- $f$ L-stetig $\iff$ $\forall x \in X : \| f'(x) \| \le L_f$