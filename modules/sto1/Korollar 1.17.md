Sei $P$ ein [[Maß|Wahrscheinlichkeitsmaß]] auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$

Die [[Verteilungsfunktion]] $F : \mathbb{R} \to \mathbb{R}$ sei definiert durch

$$
	F(x) = P((-\infty, x], x \in \mathbb{R})
$$

$P$ ist eindeutig auf $\mathcal{L}$ bestimmt.

---

Sei $\mu$ ein [[Maß|endliches]] [[Maß]] auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}^d$ mit
- $S = \prod_{i = 1}^d (a_1, b_1]$
- $S_{(x_1, \dots, x_d)} = \prod_{i = 1}^d (-\infty, x]$

Die [[Verteilungsfunktion]] $F$ sei definiert durch

$$
	F(x_1, \dots, x_d) = \mu(S_{(x_1, \dots, x_d)})
$$

Es gilt mit der [[modules/sto1/Satz 1.7|Siebformel]]

$$
	\mu(S) = \Delta_S F = \sum_{(\varepsilon_1, \dots, \varepsilon_d) \in \{ 0, 1 \}^d} (-1)^{\sum_{i=1}^d \varepsilon_i} F\left( \sum_{i = 1}^d \varepsilon_i a_i + (1 - \varepsilon_i) b_i \right)
$$

Es gilt
- $\Delta_S F \ge 0$
- $x_n^d \downarrow x^d \implies \lim_{n \to \infty} F(x_n^d) = F(x)$ mit $\forall i \in \{ 1, \dots, d \} : x_n^{(i)} \downarrow x^{(i)}$