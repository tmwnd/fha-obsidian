Sei $\mathscr{B}^d$ die Borelsche $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]], $P, (P_n)_{n \in \mathbb{N}}$ [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaße]] auf $(\mathbb{R}^d, \mathscr{B}^d)$ mit den [[zettel/Verteilungsfunktion|Verteilungsfunktionen]] $F, (F_n)_{n \in \mathbb{N}}$.

Wir betrachten folgende Aussagen
- a) $\forall f : \mathbb{R}^d \to \mathbb{R}$ mit $f$ beschränkt, (gleichmäßig) stetig gilt

$$
	\lim_{n \to \infty} \int f dP_n = \int f dP
$$

- b) $\forall O \subseteq \mathbb{R}^d$ mit $O$ offen gilt

$$
	\liminf_{n \to \infty} P_n(O) \ge P(O)
$$

- c) $\forall A \subseteq \mathbb{R}^d$ mit $A$ abgeschlossen gilt

$$
	\limsup_{n \to \infty} P_n(A) \le P(A)
$$

- d) $\forall C \in \mathscr{B}^d$ mit $C$ $P$-[[zettel/Topologischer Rand|randlos]] gilt

$$
	\lim_{n \to \infty} P_n(C) = P(C)
$$

- e) Für jede Stetigkeitsstelle $x$ von $f$ gilt

$$
	\lim_{n \to \infty} F_n(x) = F(x)
$$

Es gilt
- a) $\iff$ b) $\iff$ c) $\iff$ d) $\iff$ e).