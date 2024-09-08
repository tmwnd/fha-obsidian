Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $N \in \mathcal{A}$ eine $P_{\vartheta_0}$-[[zettel/μ-Nullmenge|Nullmenge]], $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $\Theta \subseteq \mathbb{R}$ ein offenes Intervall, $\vartheta_0$ der zugrundeliegende Parameter, $(\vartheta_n)_{n \in \mathbb{N}} : \Omega \to \Theta$ eine [[zettel/Funktion|Funktion]] mit
- $\forall \vartheta \in \Theta : P_\vartheta^{X_1} \ll \mu$
- $\forall \vartheta \in \Theta : P_\vartheta^{X_1}$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) \mid x \in R$
- $\forall \vartheta_1, \vartheta_2 \in \Theta, \vartheta_1 \ne \vartheta_2 : P_{\vartheta_1}^{X_1} \ne P_{\vartheta_2}^{X_1}$
- $A := \{ x \in R \mid f(x, \vartheta) \gt 0 \}$ unabhängig von $\vartheta \in \Theta$
- $\forall x \in \mathcal{A} : \vartheta \mapsto f(x, \vartheta) \in C^1 \mid \vartheta \in \Theta$

Es gilt
- $\forall \omega \in N^\complement : \left. \sum_{i=0}^n \frac{d}{d\vartheta} \log(f(X_i(\omega), \vartheta)) \right|_{\vartheta=\vartheta_n(\omega)} = 0$
- $\forall \omega \in N^\complement : \lim_{n \to \infty} \vartheta_n(\omega) = \vartheta_0$