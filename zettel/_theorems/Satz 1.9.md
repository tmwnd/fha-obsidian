Sei $\mathcal{R}$ ein [[zettel/Ring|Ring]] auf $\Omega$ und $\mu : \mathcal{R} \to \overline{\mathbb{R}}_+$ ein endlich-additives [[zettel/Maß|Maß]].

Wir betrachten die folgenden Konvergenzaussagen:
- a) $\mu$ ist $\sigma$-additiv
- b) Stetigkeit von unten:
	- $(A_n)_{n \in \mathbb{N}} \in \mathcal{R}$ mit $A_n \uparrow A \in \mathcal{R} \implies$

$$
	\lim_{n \to \infty} \mu(A_n) = \mu(A)
$$

- c) Stetigkeit von oben
	- $(A_n)_{n \in \mathbb{N}} \in \mathcal{R}$ mit $A_n \downarrow A \in \mathcal{R} \land \mu(A_1) \lt \infty \implies$

$$
	\lim_{n \to \infty} \mu(A_n) = \mu(A)
$$

- d) $\emptyset$-Stetigkeit
	- $(A_n)_{n \in \mathbb{N}} \in \mathcal{R}$ mit $A_n \downarrow \emptyset \land \mu(A_1) \lt \infty \implies$

$$
	\lim_{n \to \infty} \mu(A_n) \lt \infty
$$

Es gilt: a) $\iff$ b) $\implies$ c) $\implies$ d).

---

$\forall A \in \mathcal{R} : \mu(A) \lt \infty \implies$ a), b), c), d) äquivalent.