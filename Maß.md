Sei $\mathcal{A}$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$.

Eine $\sigma$-[[Abbildung|additive]] [[Abbildung]] $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *Maß* auf $\mathcal{A}$.

---

Ein Maß $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *endlich* bzw. *finit*, falls
- $\mu(\Omega) < \infty$

---

Ein Maß $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt $\sigma$-*endlich*, falls eine Folge $(A_n)_{n \in \mathbb{N}} \subseteq \mathcal{A}$ existiert mit
- $\forall n \in \mathbb{N} : \mu(A_n) < \infty$
- $\Omega = \bigcup_{n \in \mathbb{N}} A_i$

$\mu$ $\sigma$-additiv $\implies$ $\mu$ endlich additiv

---

Ein Maß $P : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *Wahrscheinlichkeitsmaß*, falls
- $P(\Omega) = 1$

---

Sei $\Omega \ne \emptyset$, $\mathcal{A}$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$, $\{ \omega \} \in \mathcal{A}$.

Ein Wahrscheinlichkeitsmaß $P : \mathcal{A} \to \overline{\mathbb{R}}_+$$ heißt *diskret*, falls für eine abzählbare Menge $\Omega_0 \subseteq \Omega$ gilt
- $P(\Omega_0) = 1$

und hat durch das [[Dirac-Maß, Einpunktmaß|Dirac-Maß]] $\delta$ die Form

$$
	P = \sum_{\omega \in \Omega_0} P(\{ \omega \}) \delta_\omega
$$

---

Sei $n \in \mathbb{N}$, $\mu_1, \dots, \mu_n$ $\sigma$-endliche Maße.

Das *Produktmaß* $\mu$ ist definiert als

$$
	\mu = \bigotimes_{i=1}^n \mu_i
$$

Es gilt für $(A_n)_{n \in \mathbb{N}}$

$$
\mu\left( \prod_{i=1}^n A_i \right) \prod_{i=1}^n \mu_i(A_i)
$$