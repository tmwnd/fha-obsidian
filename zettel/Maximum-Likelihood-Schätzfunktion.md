Sei $\Theta \subseteq \mathbb{R}^k$, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$ mit
- $\forall \vartheta \in \Theta : P_\vartheta^X \ll \mu$
- $\forall \vartheta \in \Theta : P_\vartheta^X$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) \mid x \in R$

$\hat{\vartheta} : (R, \mathscr{S}) \to (\mathbb{R}^k, \mathscr{B}^k)$ heißt *Maximum-Likelihood-Schätzfunktion* für $\vartheta$, falls
- $\forall \vartheta \in \Theta : \hat{\vartheta}(x) \in \Theta$ für $P_\vartheta^X$-f. a. $x \in R$
- $\forall \vartheta \in \Theta : f(x, \hat{\vartheta}(x)) = \sup_{\vartheta \in \Theta} f(x, \vartheta)$ für $P_\vartheta^X$-f. a. $x \in R$