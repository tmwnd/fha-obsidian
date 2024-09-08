Seien $h, k, n \in \mathbb{N}_0$, $\mathcal{L} \subset \mathbb{R}^n$ ein beliebiger $k$-dimensionaler, linearer Teilraum, $\mathcal{L_0} \subset \mathcal{L}$ ein beliebiger $h$-dimensionaler, linearer Teilraum, $X = (X_n)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(\mu, \sigma^2\mathbb{1}_n)$ ein [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängiger]] [[zettel/Zufallsvariable|Zufallsvektor]], $\text{H} : \mu \in \mathcal{L}_0, \text{K} : \mu \in \mathcal{L} \setminus \mathcal{L}_0$ ein [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]] mit
- $\mu$ unbekannt
- $\sigma^2$ unbekannt, uninteressant
- $h \lt k \lt n$
- $\text{E}[X] = (\text{E}[X_i])_{i \in \{ 1, \dots, n \}} \in \mathcal{L}$
- $\forall \mu \in \mathcal{L}, \sigma^2 \gt 0 : P_{\mu, \sigma^2}(X \in \mathcal{L}) = 0$

Die Dichte von $X$ ist definiert als

$$
	f_{\mu, \sigma^2}(x) = \left. \left( \frac{1}{\sqrt{2\pi\sigma^2}} \right)^n \exp\left( -\frac{1}{2\sigma^2} |x-\mu|^2 \right) \ \right| \ x \in \mathbb{R}^n
$$

Die [[zettel/Likelihood-Quotienten-Teststatistik|Likelihood-Quotienten-Teststatistik]] $T$ des Linearen Modells ist definiert als

$$
	\Lambda(X) = \left( \frac{|X - P_\mathcal{L}(X)|}{|X - P_{\mathcal{L}_0}(X)|} \right)^\frac{n}{2}
$$

mit
- $\exists \underbrace{\underbrace{\underbrace{q_1, \dots, q_h}_{\text{ONB von } \mathcal{L}_0}, q_{h+1}, \dots, q{k}}_{\text{ONB von } \mathcal{L}}, q{k+1}, \dots, q_n}_{\text{ONB von } \mathbb{R}^n}$ eine Orthogonalbasis von $\mathbb{R}^n$
- $P_{\mathcal{L}_0}(X) := \sum_{i=1}^h (q_i^TX)q_i$
- $P_\mathcal{L}(X) := \sum_{i=1}^k (q_i^TX)q_i$


Sei $Y := (Y_i)_{i \in \{ 1, \dots, n \}} = \begin{pmatrix} q_1^T \\ \vdots \\ q_n^T \end{pmatrix}X \sim \mathcal{N}((q_i^T\mu_i)_{i \in \{ 1, \dots, n \}}, \sigma^2\mathbb{1}_n)$

Es gilt

$$
	\Lambda(X) \equiv T(X) := \frac{\frac{1}{k-h} |P_\mathcal{L}(X) - P_{\mathcal{L}_0}(X)|^2}{\frac{1}{n-k} |X - P_\mathcal{L}(X)|^2} = \frac{\frac{1}{k-h} \sum_{i=h+1}^k Y_i^2}{\frac{1}{n-k} \sum_{i=k+1}^n Y_i^2}
$$