Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $\Theta \subseteq \mathbb{R}$ ein offenes Intervall, $(d_n : (R^n, \mathscr{S}^n) \to (\mathbb{R}, \mathscr{B}))_{n \in \mathbb{N}}$ eine Folge von [[zettel/Schätzfunktion|Schätzfunktionen]], $(d_n((X_i)_{i \in \{ 1, \dots, n \}}))_{n \in \mathbb{N}}$ eine Folge von [[zettel/Schätzer|Schätzern]] mit
- $\forall \vartheta \in \Theta : P_\vartheta^{X_1} \ll \mu$
- $\forall \vartheta \in \Theta : P_\vartheta^{X_1}$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) \mid x \in R$
- $\forall \vartheta_1, \vartheta_2 \in \Theta, \vartheta_1 \ne \vartheta_2 : P_{\vartheta_1}^{X_1} \ne P_{\vartheta_2}^{X_1}$
- $A := \{ x \in R \mid f(x, \vartheta) \gt 0 \}$ unabhängig von $\vartheta \in \Theta$
- $\forall x \in \mathcal{A} : \vartheta \mapsto f(x, \vartheta) \in C^2 \mid \vartheta \in \Theta$
- $\forall \vartheta \in \Theta : \int \frac{d}{d\vartheta} f(x, \vartheta) d\mu(x) = 0$
- $\forall \vartheta \in \Theta : \int \frac{d^2}{d\vartheta^2} f(x, \vartheta) d\mu(x) = 0$
- $\forall \vartheta \in \Theta : 0 \lt i_{X_1}(\vartheta) \lt \infty$
- $\forall \vartheta_0 \in \Theta, \exists \delta \gt 0 : (\vartheta_0 - \delta, \vartheta_0 + \delta) \subseteq \Theta$ 
- $\forall \vartheta_0 \in \Theta, \exists M : (R, \mathscr{S}) \to (\mathbb{R}, \mathscr{B}), \forall x \in A, \vartheta \in (\vartheta_0 - \delta, \vartheta_0 + \delta) : \text{E}_{\vartheta_0}[M(x)] \lt \infty$
- $\forall \vartheta_0 \in \Theta, \exists M : (R, \mathscr{S}) \to (\mathbb{R}, \mathscr{B}), \forall x \in A, \vartheta \in (\vartheta_0 - \delta, \vartheta_0 + \delta) : \left| \frac{d^2}{d\vartheta^2} \log(f(x, \vartheta)) \right| \le M(x)$
- $\forall n \in \mathbb{N} : \hat{\vartheta}_n : (R^n, \mathscr{S}^n) \to (\Theta, \mathscr{B}_\Theta)$
- $\forall \vartheta \in \Theta : \hat{\vartheta}_n((X_i)_{i \in \{ 1, \dots, n \}}) \overset{P_\vartheta}{\longrightarrow} \vartheta$
- $\forall \vartheta \in \Theta : \frac{1}{\sqrt{n}} \sum_{i=1}^n \left. \frac{d}{d\vartheta} \log(f(X_i, \vartheta)) \right|_{\vartheta=\hat{\vartheta}((X_i)_{i \in \{ 1, \dots, n \}})} \overset{P_\vartheta}{\longrightarrow} 0$
- $\forall \vartheta \in \Theta, \exists \sigma^2 := \text{Var}[\vartheta] \in (0, \infty) : \sqrt{n}(d_n((X_i)_{i \in \{ 1, \dots, n \}})) \overset{V}{\longrightarrow} \mathcal{N}(0, \sigma^2)$

Es gilt

$$
	\exists N \in \mathscr{B}_\vartheta, \forall \vartheta \in N^\complement : \text{Var}[\vartheta] \ge i_{X_1}(\vartheta)^{-1}
$$

und
- $(d_n)_{n \in \mathbb{N}}$ ist [[zettel/Schätzer/Asymptotische Effizienz|asymptotisch effizient]]