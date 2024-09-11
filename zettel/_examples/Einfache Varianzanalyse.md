Sei $(n_i)_{i \in \{ 1, \dots, s \}} \in \mathbb{N}$, $Z_{i, j} := (Z_{i, j})_{j \in \{ 1, \dots, n_i \}, i \in \{ 1, \dots, s \}} \sim N(0, \sigma^2)$ ein [[zettel/Schema von Zufallsvariablen/Stochastische Unabhängigkeit|unabhängiges]] [[zettel/Schema von Zufallsvariablen|Schema von Zufallsvariablen]], $(\alpha_i)_{i \in \{ 1, \dots, s \}} \in \mathbb{N}$ beliebig, $X_{i, j} := \alpha_i + Z_{i, j}$, $X := (X_{1, 1}, \dots, X_{1, n_1}, \dots, X_{s, 1}, \dots X_{s, n_s})$, $(q_i = \frac{1}{\sqrt{n_i}} (\underbrace{0, \dots, 0}_{\sum_{j=1}^{i-1} n_j \text{-fach}}, \underbrace{1, \dots, 1}_{n_i \text{-fach}}, \underbrace{0, \dots, 0}_{\sum_{j=i+1}^{s} n_j \text{-fach}})^T)_{i \in \{ 1, \dots, s \}}$, $q = \frac{1}{\sqrt{n}} (1)_{i \in \{ 1, \dots, s \}}$, $\overline{X_{i, \cdot}} := \frac{1}{n_i} \sum_{j=1}^{n_i} X_{i, j}$, $\mathcal{L} := \{ \sum_{i=1}^s c_i \cdot q_i \mid (c_i)_{i \in \{ 1, \dots, s \}} \in \mathbb{R} \}$, $\mathcal{L}_0 := \{ c \cdot q \mid c \in \mathbb{R} \}$, $\text{H} : \forall i, j \in \{ 1, \dots, s \} : \alpha_i = \alpha_j, \text{K} : \exists i, j \in \{ 1, \dots, s \}, \alpha_i \ne \alpha_j$ ein [[zettel/Lineares Modell|Lineares Modell]], $\alpha$ das vorgegebene Testniveau mit
- $\sigma^2 \gt 0$ unbekannt
- $n := \sum_{i=1}^s n_i \gt s$
- $P_\mathcal{L}(X) = \sum_{i=1}^s \sqrt{n_i} \cdot \overline{X_{i, \cdot}} \cdot q_i$
- $P_{\mathcal{L}_0}(X) = \sum_{i=1}^s \sqrt{n_i} \cdot \overline{X}q_i = \sqrt{n} \cdot \overline{X}q$

Die [[zettel/Likelihood-Quotienten-Teststatistik|Likelihood-Quotienten-Teststatistik]] $T$ ist definiert als

$$
	T(X) := \frac{\frac{1}{s-1} \sum_{i=1}^s n_i (\overline{X_{i, \cdot}} - \overline{X})^2}{\frac{1}{n-s} \sum_{i=1}^s \sum_{j=1}^{n_i} (X_{i, j} - \overline{X_{i, \cdot}})^2}
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ der einfachen Varianzanalyse ist definiert als

$$
	\varphi(X) := \begin{cases}
		1, \quad & T(X) \gt c \\
		0, \quad & T(X) \le c
	\end{cases}
$$

mit
- $T(X) \sim F_{s-1, n-1}$, falls $\text{H}$ gültig ist
- $c := F_{s-1, n-1, 1-\alpha}$