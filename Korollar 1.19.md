Sei $F : \mathbb{R}^d \to \mathbb{R}$ eine Funktion mit
- $\Delta_S F \ge 0$
- $x_n^d \downarrow x^d \implies \lim_{n \to \infty} F(x_n^d) = F(x)$ mit $\forall i \in \{ 1, \dots, d \} : x_n^{(i)} \downarrow x^{(i)}$
- $\forall i \in \{ 1, \dots, d \} : x_1, \dots, x_{i - 1}, x_{i + 1}, \dots, x_d \in \mathbb{R} \implies$

$$
	\lim_{x \to -\infty} F(x_1, \dots, x_{i - 1}, x, x_{i + 1}, \dots, x_d) = 0
$$

Falls $a \in \mathbb{R}$ exisitert mit
- $\lim_{min(x_1, \dots, x_d) \to +\infty} F(x_1, \dots, x_d) = a$

Dann existiert genau ein [[Maß]] $\mu$ auf der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}^d$ mit

$$
	\forall (x_1, \dots, x_d) \in \mathbb{R}^d : \mu(S_{(x_1, \dots, x_d)}) = F(x_1, \dots, x_d)
$$

---

Es gilt
- $\mu(\mathbb{R}^d) = a$
- $a = 1$ $\implies$ $\mu$ ist ein [[Maß|Wahrscheinlichkeitsmaß]], $F$ ist eine [[Verteilungsfunktion]] gemäß des korrespondierenden [[Maß|Wahrscheinlichkeitsmaßes]] $P$.