TODO

Sei $(\Omega, d)$ ein metrischer Raum, $A \subseteq \Omega$, $\omega \in \Omega$, $\varepsilon \gt 0$.

Es sei definiert
- Die *$\varepsilon$-Kugel* um $\omega$

$$
	K_\varepsilon(\omega) = \{ \omega' \in \Omega \mid d(\omega, \omega') \lt \varepsilon \}
$$

- Der *Rand* von $A$

$$
	\partial A = \{ \omega \in \Omega \mid \forall \varepsilon \gt 0 : K_\varepsilon(\omega) \cap A \ne \emptyset \land K_\varepsilon(\omega) \cap A^\complement \ne \emptyset \}
$$

- $A$ heißt *offen*, falls $A = A \setminus \partial A$
- $A$ heißt *abgeschlossen*, falls $A = A \cup \partial A$
- $A$ heißt *kompakt*, falls jede offene Überdeckung von $A$ eine endliche Teilüberdeckung von $A$ enthält

$$
	A \subseteq \bigcup_{n \in \mathbb{N}} A_n, \forall n \in \mathbb{N} : A_n \text{ offen } \implies \exists n \in \mathbb{N} : A \subseteq \bigcup_{i=1}^n A_i
$$

- $\mathcal{O}(\Omega)$ ist das System der offenen Mengen von $\Omega$
- $\mathcal{A}(\Omega)$ ist das System der abgeschlossenen Mengen von $\Omega$
- $\mathcal{K}(\Omega)$ ist das System der kompakten Mengen von $\Omega$
- $\mathcal{B}(\Omega) = \sigma(\mathcal{O}(\Omega))$ ist die $\sigma$-[[zettel/σ-Algebra|Algebra]] der *Borelmengen* auf $\Omega$.

---

Eine Teilmenge in $\mathbb{R}^n$ ist kompakt, falls sie beschränkt und abgeschlossen ist.