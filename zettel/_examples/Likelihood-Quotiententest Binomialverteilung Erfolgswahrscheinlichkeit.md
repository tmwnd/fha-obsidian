Sei $X \sim \mathfrak{B}(n, p)$, $p_0, p_1 \in (0, 1)$ beliebig, $\text{H} : p = p_0, \text{K} : p = p_1$ ein [[zettel/Likelihood-Quotiententestproblem|Likelihood-Quotiententestproblem]], $\alpha$ das vorgegebene Testniveau mit
- $n \in \mathbb{N}$ bekannt
- $p \in \{ p_0, p_1 \}$ unbekannt
- $p_0 \lt p_1$

Der [[zettel/Testfunktion|Testfunktion]] $\varphi : \{ 0, \dots, n \} \to [0, 1]$ des gegebenen statistischen Testproblems ist definiert als

$$
	\varphi(x) := \left. \begin{cases}
		1, \quad & x \gt c \\
		\gamma, \quad & x = c \\
		0, \quad & x \lt c
	\end{cases} \ \right| \ x \in \{ 0, \dots, n \}
$$

mit
- $c := \min\{ x \in \{ 0, \dots, n \} \mid P_{p_0}(X \gt x) \le \alpha \}$ das kleinste $(1-\alpha)$-Quantil von $\mathfrak{B}(n, p_0)$
- $\gamma := \begin{cases} \frac{\alpha - P_{p_0}(X \gt c)}{P_{p_0}(X = c)} \in (0, 1], \quad & P_{p_0}(X \gt c) \lt \alpha \\ 0, \quad & P_{p_0}(X = c) = 0 \end{cases}$

Der Likelihood-Quotient ist definiert als

$$
	\frac{P_{p_1}(X = x)}{P_{p_0}(X = x)} = \frac{\binom{n}{x} p_1^x (1-p_1)^{n-x}}{\binom{n}{x} p_0^x (1-p_0)^{n-x}} = \left( \frac{p_1 (1-p_0)}{p_0 (1-p_1)} \right)^x \left( \frac{1-p_1}{1-p_0} \right)^n
$$

mit

$$
	k := \left( \frac{p_1 (1-p_0)}{p_0 (1-p_1)} \right)^c \left( \frac{1-p_1}{1-p_0} \right)^n \gt 0
$$

Es gilt
- $\forall x \in (0, \dots, n) : x \lesseqqgtr c \iff P_{p_1}(X = x) \lesseqqgtr k \cdot P_{p_0}(X = x)$
- $\text{E}_{p_0}[\varphi(X)] = \alpha$