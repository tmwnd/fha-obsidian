Sei $(X_{n, l})_{l \in \{ 1, \dots, k_n \}, n \in \mathbb{N}}$ ein [[zettel/Schema von Zufallsvariablen|Schema von Zufallsvariablen]] mit
- $\forall n \in \mathbb{N}, l \in \{ 1, \dots, k_n \} : \sigma_{n, l}^2 := \text{Var}[X_{n, l}] \lt \infty$
- $\forall n \in \mathbb{N} : S_n := \sum_{l=1}^{k_n} X_{n, l}$
- $\forall n \in \mathbb{N} : s_n^2 := \sum_{l=1}^{k_n} \sigma_{n, l}^2 = \text{Var}[S_n]$

Die *Feller-Bedingung* ist erfüllt, falls

$$
	\lim_{n \to \infty} \max_{1 \le l \le k_n} \frac{\sigma_{n, l}^2}{s_n^2} = 0
$$