Sei $A \subseteq \Omega$, $\omega \in \Omega$.

Die *Indikatorfunktion* $I_A : \Omega \to \mathbb{R}$ ist definiert als

$$
	I_A(\omega) = \begin{cases}
		1, \quad \omega \in A \\
		0, \quad \omega \notin A
	\end{cases}
$$

---

Sei $A \subseteq \Omega$, $\mathcal{A}$ die $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$.

$I_A$ ist genau dann [[Funktion|messbar]], falls
- $A \in \mathcal{A}$

---

Sei $f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ [[Funktion|messbar]] mit existierendem $\mu$-[[mu-Integral|Integral]], $A \in \mathcal{A}$.

Schreibe

$$
	\int f I_A d\mu = \int_A f d\mu
$$