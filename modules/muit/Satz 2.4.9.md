Sei $\mathcal{A} \subseteq \mathcal{P}(\Omega)$, $\mu : \mathcal{A} \to [0, \infty]$ mit
- $\Omega \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
- $\mathcal{A}$ ist $\cap$-[[Menge vereinigungsstabil|stabil]]
- $\mu(\emptyset) = 0$
- $\forall (A_n)_{n \in \mathbb{N}} \subseteq \mathcal{A} \text{ p. d. }, \bigcup_{n \in \mathbb{n}} A_n \in \mathcal{A} : \mu\left( \bigcup_{n \in \mathbb{N}} A_n \right) = \sum_{n \in \mathbb{N}} \mu(A_n)$

Es existiert ein [[Maß]] $\hat{\mu}$ als Fortsetzung von $\mu$ mit
- $\forall A \in \mathcal{A} : \mu(A) = \hat{\mu}(A)$
- $(\Omega, \sigma(\mathcal{A}), \hat{\mu})$ ist ein [[Maßraum]]

$\hat{\mu}$ ist eindeutig bestimmt, falls
- $\exists (E_n)_{n \in \mathbb{N}} \subseteq \mathcal{A} : E_n \uparrow \Omega, \forall n \in \mathbb{N} : \mu(E_n) \lt \infty$