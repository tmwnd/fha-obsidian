Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $q_1 := (\frac{1}{\sqrt{n}})_{i \in \{ 1, \dots, n \}}$, $\mathcal{L} := \{ c \cdot q_1, c \in \mathbb{R} \}$, $\mathcal{L}_0 := \{ 0 \}$, $\text{H} : \mu = 0, \text{K} : \mu \ne 0$ ein [[zettel/Lineares Modell|Lineares Modell]], $\alpha$ das vorgegebene Testniveau mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma^2 \gt 0$ unbekannt, uninteressant

Es gilt
- $k := \dim(\mathcal{L}) = 1$
- $h := \dim(\mathcal{L}_0) = 0$
- $q_1^TX = \sqrt{n} \cdot \overline{X} = \sqrt{n} \frac{1}{n} \sum_{i=1}^n X_i$

und

$$
	\sum_{i=2}^n (q_i^TX)^2 = \sum_{i=1}^n (q_i^TX)^2 - n \cdot \overline{X}^2 = \sum_{i=1}^n X_i^2 - n \cdot \overline{X}^2 = \sum_{i=1}^n (X_i - \overline{X})^2
$$

Die [[zettel/Likelihood-Quotienten-Teststatistik|Likelihood-Quotienten-Teststatistik]] $t$ ist definiert als

$$
	t(X) := \frac{\sqrt{n} \cdot \overline{X}}{\sqrt{\frac{1}{n-1} \sum_{i=1}^n (X_i - \overline{X})^2}}
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ des $t$-Tests  im Einstichprobenfall ist definiert als

$$
	\varphi(X) := \begin{cases}
		1, \quad & t(X) \gt c \\
		0, \quad & t(X) \le c
	\end{cases}
$$

mit
- $t(X) \sim t_{n-1}$
- $c := t_{n-1, 1-\frac{\alpha}{2}}$

---

Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $\mu_0 \in \mathbb{R}$, $\tilde{X} := (\tilde{X}_i)_{i \in \{ 1, \dots, n \}} := (X_i - \mu_0)_{i \in \{ 1, \dots, n \}}$, $q_1 := (\frac{1}{\sqrt{n}})_{i \in \{ 1, \dots, n \}}$, $\mathcal{L} := \{ c \cdot q_1, c \in \mathbb{R} \}$, $\mathcal{L}_0 := \{ \mu_0 \}$, $\text{H} : \mu = \mu_0, \text{K} : \mu \ne 0$ ein [[zettel/Lineares Modell|Lineares Modell]], $\alpha$ das vorgegebene Testniveau mit
- $\mu \in \mathbb{R}$ unbekannt
- $\sigma^2 \gt 0$ unbekannt, uninteressant

Das gegebene Lineare Modell ist Äuivalent zu dem Linearen Modell $\text{H} : \mu = 0, \text{K} : \mu \ne 0$ als [[zettel/Statistischer Test|Statistischer Test]] für $\tilde{X}$.