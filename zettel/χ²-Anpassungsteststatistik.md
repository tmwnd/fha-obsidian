Seien $(S_i)_{i \in \{ 1, \dots, n \}} \sim \mathfrak{M}(n, (p_i)_{i \in \{ 1, \dots, r \}})$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]], $(\pi_i)_{i \in \{ 1, \dots, r \}} \in (0, 1)$ beliebig, $\text{H} : \forall i \in \{ 1, \dots, r \} : p_i = \pi_i, \text{K} : \exists i \in \{ 1, \dots, r \} : p_i \ne \pi_i$ ein [[zettel/Statistisches Testproblem|statistisches Testproblem]], $\alpha$ das vorgegebene Testniveau mit
- $(p_i)_{i \in \{ 1, \dots, r \}} \in (0, 1)$ bekannt
- $\sum_{i=1}^r p_i = 1$ 
- $\sum_{i=1}^r \pi_i = 1$

Es gilt
- $\frac{1}{n} S \overset{P}{\longrightarrow} p$

Sei $S := (S_i)_{i \in \{ 1, \dots, n-1 \}}$, $p := (p_i)_{i \in \{ 1, \dots, r-1 \}}$, $\pi := (\pi_i)_{i \in \{ 1, \dots, r-1 \}}$, $\Sigma := \text{diag}(\pi) - \pi\pi^2$ mit
- $\text{H} \equiv p = \pi, \text{K} \equiv p \ne \pi$
- $\Sigma^{-1} = \text{diag}((\frac{1}{\pi_i})_{i \in \{ 1, \dots, r-1 \}}) - \frac{1}{\pi} \mathbb{1}_{(r-1) \times (r-1)}$

Die *$\chi^2$-Anpassungsteststatistik* $T$ ist definiert als

$$
	T_n(S) := \sum_{i=1}^{r-1} \frac{(S_i - m\pi_i)^2}{m\pi_i}
$$

Der [[zettel/Statistischer Test|statistischer Test]] $\varphi(X)$ der $\chi^2$-Anpassungsteststatistik ist definiert als

$$
	\varphi(X) := \begin{cases}
		1 & T(X) \gt c \\
		0 & T(X) \le c
	\end{cases}
$$

Es gilt
- $T_n(S) \to X \sim \chi_{r-1}^2$, falls $\text{H}$ gültig ist
- $c := \chi_{r-1, 1-\alpha}^2$
- Der gegebene statistische Test hält das Testniveau asymptotisch exakt ein