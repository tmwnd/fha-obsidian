Sei $\mathcal{A}$ eine $\sigma$-[[sigma-Algebra|Algebra]].

Eine $\sigma$-additive [[Abbildung]] $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *Maß* auf $\mathcal{A}$

---

Ein Maß $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *endlich*, falls
- $\mu(\Omega) < \infty$

---

Ein Maß $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt $\sigma$-*endlich*, falls eine Folge $\exists (A_n)_{n \in \mathbb{N}} \subseteq \mathcal{A}$ mit
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

und hat die Form

$$
	P = \sum_{\omega \in \Omega_0} P(\{ \omega \}) \delta_\omega
$$

---

Seien $\mu_1, \mu_2$ $\sigma$-endliche Maße.

Das *Produktmaß* $\tilde{\mu}$ ist definiert als

$$
	\tilde{\mu} = \mu_1 \otimes \mu_2
$$