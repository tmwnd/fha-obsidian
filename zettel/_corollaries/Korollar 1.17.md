Sei $P$ ein [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]] auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathscr{B}$.

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ sei definiert durch

$$
	F(x) = P((-\infty, x], x \in \mathbb{R})
$$

$P$ ist eindeutig auf $\mathscr{B}$ bestimmt.

---

Sei $\mu$ ein [[zettel/Maß|endliches]] TODO [[zettel/Maß|Maß]] auf der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathscr{B}^d$ mit
- $S = \prod_{i = 1}^d (a_1, b_1]$
- $S_{(x_1, \dots, x_d)} = \prod_{i = 1}^d (-\infty, x]$

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] $F$ sei definiert durch

$$
	F(x_1, \dots, x_d) = \mu(S_{(x_1, \dots, x_d)})
$$

Es gilt mit der [[zettel/_theorems/Satz 1.7|Siebformel]]

$$
	\mu(S) = \Delta_S F = \sum_{(\varepsilon_1, \dots, \varepsilon_d) \in \{ 0, 1 \}^d} (-1)^{\sum_{i=1}^d \varepsilon_i} F\left( \sum_{i = 1}^d \varepsilon_i a_i + (1 - \varepsilon_i) b_i \right)
$$

Es gilt
- $\Delta_S F \ge 0$
- $x_n^d \downarrow x^d \implies \lim_{n \to \infty} F(x_n^d) = F(x)$ mit $\forall i \in \{ 1, \dots, d \} : x_n^{(i)} \downarrow x^{(i)}$