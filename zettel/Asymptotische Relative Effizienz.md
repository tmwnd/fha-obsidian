Sei, $X$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $B_1(X), B_2(X)$ [[zettel/Konfidenzbereichsschätzer|Konfidenzbereichsschätzer]], $N_{\gamma, \vartheta}(\cdot) := \inf \{ n \in \mathbb{N} \mid \forall m \ge n : \text{E}_\vartheta[V_m(\cdot)] \le \gamma \}$.

Die *asymptotische relative Effizienz* $\text{arve}_\vartheta$ ist definiert als

$$
	\text{arve}_\vartheta(B_1, B_2) := \lim_{\gamma \to 0^+} \frac{N_{\gamma, \vartheta}(B_2)}{N_{\gamma, \vartheta}(B_1)}
$$

falls
- $\lim_{n \to \infty} n^\frac{d}{2}\text{E}_\vartheta[V_n(\cdot)] \in (0, \infty)$