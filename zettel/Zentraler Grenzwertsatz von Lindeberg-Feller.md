Sei $(X_{n, l})_{l \in \{ 1, \dots, k_n \}, n \in \mathbb{N}}$ ein [[zettel/Schema von Zufallsvariablen|Schema von Zufallsvariablen]] mit
- $\forall n \in \mathbb{N}, l \in \{ 1, \dots, k_n \} : 0 \lt \sigma_{n, l}^2 := \text{Var}[X_{n, l}] \lt \infty$
- $\forall n \in \mathbb{N} : S_n := \sum_{l=1}^{k_n} X_{n, l}$
- $\forall n \in \mathbb{N} : s_n^2 := \sum_{l=1}^{k_n} \sigma_{n, l}^2 = \text{Var}[S_n]$
- $\forall n \in \mathbb{N} : s_n := \sqrt{s_n^2}$

Wir betrachten folgende Aussagen
- a) $\exists \delta \gt 0, \forall n \in \mathbb{N}, l \in \{ 1, \dots, k_n \} : \text{E}\left[ |X_{n, l}|^{2+\delta} \right] \lt \infty$ und die [[zettel/Ljapunow-Bedingung|Ljapunow-Bedingung]] ist erfüllt
- b) Die [[zettel/Lindeberg-Bedingung|Lindeberg-Bedingung]] ist erfüllt
- c) Der [[zettel/Zentraler Grenzwertsatz von Lindeberg-Lévy|Zentraler Grenzwertsatz von Lindeberg-Lévy]] gilt und der [[zettel/Feller-Bedingung|Feller-Bedingung]] ist erfüllt
- d) Der [[zettel/Zentraler Grenzwertsatz von Lindeberg-Lévy|Zentraler Grenzwertsatz von Lindeberg-Lévy]] gilt und $\forall \varepsilon \gt 0 : \lim_{n \to \infty} \max_{l \in \{ 1, \dots, k_n \}} P\left(\left| \frac{X_{n, l}}{s_n} \right| \ge \varepsilon \right) = 0$
- e) Der [[zettel/Zentraler Grenzwertsatz von Lindeberg-Lévy|Zentraler Grenzwertsatz von Lindeberg-Lévy]] gilt

Es gilt
- a) $\implies$ b) $\iff$ c) $\iff$ d) $\implies$ e)