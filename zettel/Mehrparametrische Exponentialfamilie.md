Sei $\emptyset \ne \Theta \subseteq \mathbb{R}^k$ offen und konvex, $\mu$ ein [[zettel/Maß/σ-Endlichkeit|σ-endliches]] [[zettel/Maß|Maß]] auf $(R, \mathscr{S})$, $c : \Theta \to (0, \infty)$, $h : (E, \mathscr{S}) \to (\mathbb{R}, \mathscr{B})$ nicht-negativ, $T : (R, \mathscr{S}) \to (\mathbb{R}^k, \mathscr{B}^k)$ eine suffiziente Statistik mit
- $\forall \gamma \in \mathbb{R}, 0 \ne a \in \mathbb{R}^k : \mu(a^TT \ne \gamma, h \ne 0) \gt 0$

Die Familie der Verteilungen $\mathcal{P}^X := \{ P_\vartheta^X \mid \vartheta \in \Theta \}$ heißt *$k$-parametrische Exponentialfamilie*, falls
- $\forall \vartheta \in \Theta : P_\vartheta^X$ hat die [[zettel/μ-Dichte|μ-Dichte]] $f(x, \vartheta) := c(\vartheta) \cdot e^{\vartheta^T \cdot T(x)} \cdot h(x)$

---

Es gilt
- $m(\vartheta) := \int e^{\vartheta^T \cdot T} h d\mu \mid \vartheta \in \Theta$ beliebig oft differenzierbar
- $c(\vartheta) := \frac{1}{m(\vartheta)} \mid \vartheta \in \Theta$ beliebig oft differenzierbar

und

$$
	\forall \vartheta = (\vartheta_i)_{i \in \{ 1, \dots, k \}} \in \Theta : \text{E}_\vartheta[T(X)] = \left( \frac{\partial}{\partial_i} (-\log(c(\vartheta))) \right)_{i \in \{ 1, \dots, k \}}^T
$$

und

$$
	\forall \vartheta = (\vartheta_i)_{i \in \{ 1, \dots, k \}} \in \Theta : \text{Cov}_\vartheta[T(X)] = J_T(\vartheta) = \left( \frac{\partial^2}{\partial\vartheta_i\vartheta_j} (-\log(c(\vartheta))) \right)_{i, j \in \{ 1, \dots, k \}} = i_X(\vartheta)
$$

und
- $\forall 0 \ne a \in \mathbb{R}^k : a^T\text{Cov}_\vartheta[T(X)]a = \text{Var}_\vartheta[a^T \cdot T(X)] \gt 0$