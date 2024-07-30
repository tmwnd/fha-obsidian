Sei $\emptyset \ne \Theta \subseteq \mathbb{R}$ ein offenes Intervall, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $c : \Theta \to (0, \infty)$, $h : (E, \mathscr{S}) \to (\mathbb{R}, \mathcal{L})$ nicht-negativ, $T : (R, \mathscr{S}) \to (\mathbb{R}, \mathcal{L})$ eine suffiziente Statistik mit
- $\forall \gamma \in \mathbb{R} : \mu(T \ne \gamma, h \gt 0) \gt 0$

Die Familie der Verteilungen $\mathcal{P}^X := \{ P_\vartheta^X \mid \vartheta \in \Theta \}$ heißt *einparametrische Exponentialfamilie*, falls
- $\forall \vartheta \in \Theta : P_\vartheta^X$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) := c(\vartheta) \cdot e^{\vartheta \cdot T(x)} \cdot h(x)$

Schreibe
- $dP_\vartheta^X(x) = c(\vartheta) \cdot e^{\vartheta \cdot T(x)} d\mu(x)$

---

Sei $\nu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] mit
- $\forall B \in \mathscr{S} : \nu(B) := \int_B h d\mu$
- $\forall \theta \in \Theta : P_\vartheta^X \ll \nu$

und

$$
	\forall \vartheta \in \Theta : dP_\vartheta^X(x) = c(\vartheta) \cdot e^{\vartheta \cdot T(x)} d\nu(x)
$$

---

Es gilt
- $\forall \vartheta_0 \in \Theta : \nu \ll P_{\vartheta_0}^X$
- $\forall \vartheta_0, \vartheta \in \Theta : P_\theta^X \ll P_{\vartheta_0}^X$

mit

$$
	dP_\vartheta^X(x) = \frac{c(\vartheta)}{c(\vartheta_0)} \cdot e^{(\vartheta - \vartheta_0) \cdot T(x)} dP_{\vartheta_0}^X(x)
$$

und
- $P_\vartheta^{T(X)} \ll P_{\vartheta_0}^{T(X)}$

mit

$$
	dP_\vartheta^{T(X)}(t) = \frac{c(\vartheta)}{c(\vartheta_0)} \cdot e^{(\vartheta - \vartheta_0) \cdot t} dP_{\vartheta_0}^{X(t)}(t)
$$

---

Sei $\eta$ eine offene Umgebung um $0$.

Es gilt

$$
	\frac{c(\eta + \vartheta_0)}{c(\vartheta_0)} = \frac{1}{\int e^{\eta \cdot t} dP_{\vartheta_0}^{T(x)}(t)}
$$

mit
- $c(\vartheta) = \frac{1}{\int e^{\theta \cdot T(X)} d\mu(x)}$ analytisch in $\Theta$
- $\tau(\theta) := \text{E}_\vartheta[T(X)] = -\frac{\partial}{\partial\theta} \log(c(\theta))$
- $\frac{\partial}{\partial\theta} \tau(\theta) = \text{Var}[T(x)] = i_X(\vartheta)$
- $\forall \vartheta \in \Theta : \text{Var}[T(X)] \gt 0$