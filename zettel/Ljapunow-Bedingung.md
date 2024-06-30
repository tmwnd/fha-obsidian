Sei $(X_{n, l})_{l \in \{ 1, \dots, k_n \}, n \in \mathbb{N}}$ ein [[zettel/Schema von Zufallsvariablen/Stochastische Unabhängigkeit|unabhängiges]] [[zettel/Schema von Zufallsvariablen/Zentriertheit|zentriertes]] [[zettel/Schema von Zufallsvariablen|Schema von Zufallsvariablen]] mit
- $\forall n \in \mathbb{N}, l \in \{ 1, \dots, k_n \} : 0 \lt \sigma_{n, l}^2 := \text{Var}[X_{n, l}] \lt \infty$
- $\forall n \in \mathbb{N} : S_n := \sum_{l=1}^{k_n} X_{n, l}$
- $\forall n \in \mathbb{N} : s_n^2 := \sum_{l=1}^{k_n} \sigma_{n, l}^2 = \text{Var}[S_n]$
- $\forall n \in \mathbb{N} : s_n := \sqrt{s_n^2}$

Die *Ljapunow-Bedingung* ist erfüllt, falls

$$
	\exists \delta \gt 0 : \lim_{n \to \infty} \frac{1}{s_n^{2+\delta}} \sum_{l=1}^{k_n} \text{E}\left[ |X_{n, l}|^{2+\delta} \right] = 0
$$