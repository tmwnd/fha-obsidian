Sei $\Omega$ eine beliebige Menge, $\mu^* : \mathcal{P}(\Omega) \to [0, \infty]$.

$\mu$ heißt *äußeres Maß* auf $\Omega$, falls
- $\mu^*(\emptyset) = 0$
- $\forall \emptyset \subseteq A \subseteq B \subseteq \Omega : \mu^*(A) \le \mu^*(B)$
- $\forall (A_n)_{n \in \mathbb{N}} \subseteq \mathcal{P}(\Omega) : \mu^*\left( \bigcup_{n \in \mathbb{N}} A_n \right) \lt \sum_{n \in \mathbb{N}} \mu^*(A_n)$ ($\sigma$-[[Abbildung|Subadditivität]])

---

Sei $\mu^*$ ein äußeres Maß auf $\Omega$.

Das System der $\mu^*$*-messbaren Mengen* $\mathcal{M_{\mu^*}}$ ist definiert als

$$
	\mathcal{M}_{\mu^*} = \{ M \subseteq \Omega \}
$$

---

Sie $\mu^*$ ein äußeres Maß, $\mathcal{M}_{\mu^*}$ das System der $\mu^*$-messbaren Mengen.

Es gilt
- $\mathcal{M}_{\mu^*}$ ist eine $\sigma$-[[sigma-Algebra|Algebra]]
- $\mu^*|_{\mathcal{M}_{\mu^*}}$ ist ein [[Maß]]