Sei $d \in \mathbb{D}$, $C \subseteq \mathbb{R}^d$.

Der *(topologische) Rand* $\partial C$ von $C$ ist mit der Menge der [[innere Punkte|inneren Punkte]] $\overset{\circ}{C}$ definiert als

$$
	\partial C = \overline{C} \cap (\overset{\circ}{C})^\complement
$$

---

Sei $d \in \mathbb{D}$, $C \subseteq \mathbb{R}^d$ nicht leer, $\mathcal{L}^d$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]] , $P$ ein [[Wahrscheinlichkeitsmaß]] auf $(\mathbb{R}^d, \mathcal{L}^d)$, $d_C : \mathbb{R}^d \to \mathbb{R}$ eine gleichmäßig stetige [[Funktion]], $x  \in \mathbb{R}^d$ mit

$$
	d_C(x) = \inf \{ |x - y|, y \in C \}
$$

$C$ heißt *$P$-randlos*, falls
- $P(\partial C) = 0$