Sei $\Theta \subseteq \mathbb{R}^k$, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $\hat{\vartheta}$ die [[zettel/Maximum-Likelihood-Schätzfunktion|Maximum-Likelihood-Schätzfunktion]] für $\vartheta$, $x \in R$ eine Beobachtung der [[zettel/Zufallsvariable|Zufallsvariable]] $X$ mit
- $\forall \vartheta \in \Theta : P_\vartheta^X$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) \mid x \in R$

Den [[zettel/Schätzwert|Schätzwert]] $\hat{\vartheta}(x)$ für $\vartheta$ erhalten wir durch das Lösen von

$$
	\forall j \in \{ 1, \dots, k \} : \left. \frac{\partial}{\partial\vartheta_j} \log(f(x, \vartheta)) \right|_{\vartheta=\hat{\vartheta}(x)} = 0
$$