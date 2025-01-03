Seien $(Z_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(0, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $a, b, (y_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}$ beliebig, $X_i := a + by_i + Z_i$, $\alpha := a + b\overline{y}$, $\beta := b\sigma_y$, $(t_i)_{i \in \{ 1, \dots, n \}} := \left( \frac{y_i - \overline{y}}{\sigma_y} \right)_{i \in \{ 1, \dots, n \}}$, $q_1 := \frac{1}{\sqrt{n}} (1)_{i \in \{ 1, \dots, n \}}$, $q_2 := \frac{1}{\sqrt{n}} (t_i)_{i \in \{ 1, \dots, n \}}$, $\mathcal{L} := \{ c_1 \cdot q_1 + c_2 \cdot q_2 \mid c_1, c_2 \in \mathbb{R} \}$, $\mathcal{L}_0 := \{ c \cdot q_1 \mid c \in \mathbb{R} \}$, $\text{H} : \beta = 0, \text{K} : \beta \ne 0$ ein [[zettel/Lineares Modell|Lineares Modell]], $\alpha$ das vorgegebene Testniveau mit
- $\sigma^2 \gt 0$ unbekannt
- $a, b \in \mathbb{R}$ unbekannt
- $(y_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}$ bekannt
- $\exists i, j \in \{ 1, \dots, n \} : y_i \ne y_j$

Es gilt
- $\overline{y} = \frac{1}{n} \sum_{i=1}^n y_i$
- $\sigma_y^2 = \frac{1}{n} \sum_{i=1}^n (y_i - \overline{y})^2$
- $\overline{X} = \frac{1}{n} \sum_{i=1}^n X_i$
- $\overline{Xt} = \frac{1}{n} \sum_{i=1}^n X_it_i$
- $P_\mathcal{L}(X) = \sqrt{n} \cdot \overline{X}q_1 + \sqrt{n} \cdot \overline{Xt}q_2$
- $P_{\mathcal{L}_0}(X) = \sqrt{n} \cdot \overline{X}q_1$

und

$$
	\forall i \in \{ 1, \dots, n \} : X_i = \alpha + \beta t_i + Z_i
$$

Die [[zettel/Likelihood-Quotienten-Teststatistik|Likelihood-Quotienten-Teststatistik]] $T$ ist definiert als

$$
	T(X) := \frac{\sqrt{n} \cdot |\overline{Xt}|}{\sqrt{\frac{1}{n-2} \sum_{i=1}^n (X_i - \overline{X} - \overline{Xt} \cdot t_i)^2}}
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ der einfachen linearen Regresssion ist definiert als

$$
	\varphi(X) := \begin{cases}
		1 \quad & T(X) \gt c \\
		0 \quad & T(X) \le c
	\end{cases}
$$

mit
- $T(X) \sim t_{n-2}$, falls $\text{H}$ gültig ist
- $c := t_{n-2, 1-\frac{\alpha}{2}}$