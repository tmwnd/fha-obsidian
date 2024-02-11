Seien $\mathscr{S}, \mathcal{O}, \mathcal{A}, \mathcal{K}$ [[Semiring|Semiringe]] auf $\mathbb{R}$ mit
- $\mathscr{S} = \{ (a, b], -\infty \lt a \le b \lt +\infty \}$
- $\mathcal{O} = \{ O, O \subseteq \mathbb{R} \text{ offen } \}$
- $\mathcal{A} = \{ A, A \subseteq \mathbb{R} \text{ abgeschlossen } \}$
- $\mathcal{K} = \{ K, K \subseteq \mathbb{R} \text{ kompakt } \}$

$\mathcal{L}$ heißt *Borelsche $\sigma$-[[sigma-Algebra|Algebra]]* auf $\mathbb{R}$ mit

$$
	\mathcal{L}
	= \sigma(\mathscr{S})
	= \sigma(\mathcal{O})
	= \sigma(\mathcal{A})
	= \sigma(\mathcal{K})
$$

---

Seien $\mathscr{S}^d, \mathcal{O}^d, \mathcal{A}^d, \mathcal{K}^d$ [[Semiring|Semiringe]] auf $\mathbb{R}^d$ mit
- $\mathscr{S}^d = \{ \prod_{i = 1, \dots, d} (a_i, b_i], -\infty \lt a_i \le b_i \lt +\infty \}$
- $\mathcal{O}^d = \{ O, O \subseteq \mathbb{R}^d \text{ offen } \}$
- $\mathcal{A}^d = \{ A, A \subseteq \mathbb{R}^d \text{ abgeschlossen } \}$
- $\mathcal{K}^d = \{ K, K \subseteq \mathbb{R}^d \text{ kompakt } \}$

$\mathcal{L}^d$ heißt Borelsche $\sigma$-[[sigma-Algebra|Algebra]] auf $\mathbb{R}^d$ mit

$$
	\mathcal{L}^d
	= \sigma(\mathscr{S}^d)
	= \sigma(\mathcal{O}^d)
	= \sigma(\mathcal{A}^d)
	= \sigma(\mathcal{K}^d)
$$

---

Sei $\mathcal{L}$ eine Borelsche $\sigma$-Algebra auf $\mathbb{R}$.

Die Borelsche $\sigma$-Algebra $\overline{\mathcal{L}}$ auf $\overline{\mathbb{R}}$ ist definiert als

$$
	\overline{\mathcal{L}} = \mathcal{L} \cup \{ B \cup \{ -\infty \}, B \in \mathcal{L} \} \cup \{ B \cup \{ +\infty \}, B \in \mathcal{L} \}
$$

Es gilt für die Spur-$\sigma$-[[Spur-sigma-Algebra|Algebra]] $\overline{\mathcal{L}}_\mathbb{R}$
- $\overline{\mathcal{L}}_\mathbb{R} = \mathcal{L}$

---

Die Borelsche $\sigma$-[[sigma-Algebra|Algebra]] ist [[Invarianzen|translations-]] und [[Invarianzen|spiegelungsinvariant]].
