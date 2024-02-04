Sei $\mathcal{L}^d$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]], $P, (P_n)_{n \in \mathbb{N}}$ [[Maß|Wahrscheinlichkeitsmaße]] auf $(\mathbb{R}^d, \mathcal{L}^d)$ mit den [[Verteilungsfunktion|Verteilungsfunktionen]] $F, (F_n)_{n \in \mathbb{N}}$.

Wir betrachten folgende Aussagen
- a) $\forall f : \mathbb{R}^d \to \mathbb{R}$ mit $f$ beschränkt, (gleichmäßig) stetig gilt

$$
	\lim_{n \to \infty} \int f dP_n = \int f dP
$$

- b) $\forall O \subseteq \mathbb{R}^d$ mit $O$ offen gilt

$$
	\liminf{n \to \infty} P_n(O) \ge P(O)
$$

- c) $\forall A \subseteq \mathbb{R}^d$ mit $A$ abgeschlossen gilt

$$
	\limsup_{n \to \infty} P_n(A) \le P(A)
$$

- d) $\forall C \in \mathcal{L}^d$ mit $C$ $P$-[[Topologischer Rand|randlos]] gilt

$$
	\lim_{n \to \infty} P_n(C) = P(C)
$$

- e) Für jede Stetigkeitsstelle $x$ von $f$ gilt

$$
	\lim_{n \to \infty} F_n(x) = F(x)
$$

a) $\iff$ b) $\iff$ c) $\iff$ d) $\iff$ e).