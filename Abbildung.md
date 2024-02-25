Sei $A, B \in \mathcal{A}$ mit
- $A \subseteq B$

Eine nicht-negative Abbildung $\mu : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *monoton*, falls
- $\mu(\emptyset) = 0$
- $\mu(A) \le \mu(B)$

---

Sei $n \in \mathbb{N}$.

Eine nicht-negative Abbildung $\mu : \mathcal{C} \to \overline{\mathbb{R}}_+$ heißt *(endlich) additiv*, falls
- $\mu(\emptyset) = 0$
- p. d. $A_1, \dots, A_n \in \mathcal{C}$ mit $\bigcup_{i=1}^n A_i \in \mathcal{C} \implies$

$$
	\mu\left( \bigcup_{i=1}^n A_i \right) = \sum_{i=1}^n \mu(A_i)
$$

---

Sei $n \in \mathbb{N}$.

Eine nicht-negative Abbildung $\mu : \mathcal{C} \to \overline{\mathbb{R}}_+$ heißt *(endlich) subadditiv*, falls
- $\mu(\emptyset) = 0$
- p. d. $A_1, \dots, A_n \in \mathcal{C}$ mit $\bigcup_{i=1}^n A_i \in \mathcal{C} \implies$

$$
	\mu\left( \bigcup_{i=1}^n A_i \right) \le \sum_{i=1}^n \mu(A_i)
$$

---

Eine nicht-negative Abbildung $\mu : \mathcal{C} \to \overline{\mathbb{R}}_+$ heißt $\sigma$-*additiv*, falls
- $\mu(\emptyset) = 0$
- p. d. $(A_n)_{n \in \mathbb{N}} \in \mathcal{C} \implies$

$$
	\mu\left( \bigcup_{n \in \mathbb{N}} A_n \right) = \sum_{n \in \mathbb{N}} \mu(A_n)
$$

---

Eine nicht-negative Abbildung $\mu : \mathcal{C} \to \overline{\mathbb{R}}_+$ heißt $\sigma$-*subadditiv*, falls
- $\mu(\emptyset) = 0$
- p. d. $(A_n)_{n \in \mathbb{N}} \in \mathcal{C} \implies$

$$
	\mu\left( \bigcup_{n \in \mathbb{N}} A_n \right) \le  \sum_{n \in \mathbb{N}} \mu(A_n)
$$