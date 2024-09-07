Seien $X = (X_i)_{i \in \{ 1, \dots, n \}} : (\Omega, \mathcal{A}) \to (R, \mathscr{S})$ unter jedem $P_\vartheta \in \mathcal{P}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] und identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]], $N \in \mathcal{A}$ eine $P_{\vartheta_0}$-[[zettel/μ-Nullmenge|Nullmenge]], $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $\Theta \subseteq \mathbb{R}$ ein offenes Intervall, $\vartheta_0$ der zugrundeliegende Parameter, $(\vartheta_n)_{n \in \mathbb{N}} : \Omega \to \Theta$ eine [[zettel/Funktion|Funktion]] mit
- $\forall \vartheta \in \Theta : P_\vartheta^{X_1} \ll \mu$
- $\forall \vartheta \in \Theta : P_\vartheta^{X_1}$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) \mid x \in R$
- $\forall \vartheta_1, \vartheta_2 \in \Theta, \vartheta_1 \ne \vartheta_2 : P_{\vartheta_1}^{X_1} \ne P_{\vartheta_2}^{X_1}$
- $A := \{ x \in R \mid f(x, \vartheta) \gt 0 \}$ unabhängig von $\vartheta \in \Theta$
- $\forall x \in \mathcal{A} : \vartheta \mapsto f(x, \vartheta) \in C^1 \mid \vartheta \in \Theta$
- $\forall n \in \mathbb{N}, (x_i)_{i \in \{ 1, \dots, n \}} \in \mathcal{A}$ haben die [[zettel/Likelihood-Gleichungen|Likelihood-Gleichungen]] exakt eine Lösung in $\Theta$

Es existiert die [[zettel/Maximum-Likelihood-Schätzfunktion|Maximum-Likelihood-Schätzfunktion]] $\hat{\vartheta}_n : (R^n, \mathscr{S}^n) \to (\Theta, \mathscr{B}_\Theta)$ mit

$$
	\forall (x_i)_{i \in \{ 1, \dots, n \}} : 0 = \left. \sum_{i=1}^n \log(f(x, \vartheta)) \right|_{\vartheta=\vartheta_n((x_i)_{i \in \{ 1, \dots, n \}})}
$$

Es gilt
- $\hat{\vartheta}_n((x_i)_{i \in \{ 1, \dots, n \}})$ ist [[zettel/Schätzer/Starke Konsistenz|stark konsistent]]
- $\forall \vartheta \in \Theta : \hat{\vartheta}_n((X_i(\omega))_{i \in \{ 1, \dots, n \}}) \in \Omega$ für $P_\vartheta$-f. a. $\omega \in \Omega$

und für genügend große $n \in \mathbb{N}$

$$
	\prod_{i=1}^n f(X_i(\omega), (\hat{\vartheta}((X_j(\omega))_{j \in \{ 1, \dots, n \}}))) = \sup_{\vartheta \in \Theta} \prod_{i=1}^n f(X_i(\omega), \vartheta)
$$