---
title: Indikatorfunktion
type: definition
---

Sei $A \subseteq \Omega$, $\omega \in \Omega$.

Die *Indikatorfunktion* $I_A : \Omega \to \mathbb{R}$ ist definiert als

$$
	I_A(\omega) = \begin{cases}
		1, & \omega \in A \\
		0, & \omega \notin A
	\end{cases}
$$

---

Sei $A \subseteq \Omega$, $\mathcal{A}$ die $\sigma$-[[σ-Algebra|Algebra]] auf $\Omega$.

$I_A$ ist genau dann [[Funktion|messbar]] TODO, falls
- $A \in \mathcal{A}$

---

Sei $f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ [[Funktion messbar|messbar]] mit existierendem $\mu$-[[μ-Integral|Integral]], $A \in \mathcal{A}$.

Schreibe

$$
	\int f I_A d\mu = \int_A f d\mu
$$