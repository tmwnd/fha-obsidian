Seien $\mathscr{S}, \mathcal{O}, \mathcal{A}, \mathcal{K}$ [[zettel/Semiring|Semiringe]] auf $\mathbb{R}$ mit
- $\mathscr{S} = \{ (a, b], -\infty \lt a \le b \lt +\infty \}$
- $\mathcal{O} = \{ O, O \subseteq \mathbb{R} \text{ offen } \}$
- $\mathcal{A} = \{ A, A \subseteq \mathbb{R} \text{ abgeschlossen } \}$
- $\mathcal{K} = \{ K, K \subseteq \mathbb{R} \text{ kompakt } \}$

$\mathscr{B}$ heißt *Borelsche $\sigma$-[[zettel/σ-Algebra|Algebra]]* auf $\mathbb{R}$ mit

$$
	\mathscr{B}
	= \sigma(\mathscr{S})
	= \sigma(\mathcal{O})
	= \sigma(\mathcal{A})
	= \sigma(\mathcal{K})
$$

---

Seien $\mathscr{S}^d, \mathcal{O}^d, \mathcal{A}^d, \mathcal{K}^d$ [[zettel/Semiring|Semiringe]] auf $\mathbb{R}^d$ mit
- $\mathscr{S}^d = \{ \prod_{i = 1, \dots, d} (a_i, b_i], -\infty \lt a_i \le b_i \lt +\infty \}$
- $\mathcal{O}^d = \{ O, O \subseteq \mathbb{R}^d \text{ offen } \}$
- $\mathcal{A}^d = \{ A, A \subseteq \mathbb{R}^d \text{ abgeschlossen } \}$
- $\mathcal{K}^d = \{ K, K \subseteq \mathbb{R}^d \text{ kompakt } \}$

$\mathscr{B}^d$ heißt Borelsche $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\mathbb{R}^d$ mit

$$
	\mathscr{B}^d
	= \sigma(\mathscr{S}^d)
	= \sigma(\mathcal{O}^d)
	= \sigma(\mathcal{A}^d)
	= \sigma(\mathcal{K}^d)
$$

---

Sei $\mathscr{B}$ eine Borelsche $\sigma$-Algebra auf $\mathbb{R}$.

Die Borelsche $\sigma$-Algebra $\overline{\mathscr{B}}$ auf $\overline{\mathbb{R}}$ ist definiert als

$$
	\overline{\mathscr{B}} := \mathscr{B} \cup \{ B \cup \{ -\infty \}, B \in \mathscr{B} \} \cup \{ B \cup \{ +\infty \}, B \in \mathscr{B} \}
$$

Es gilt für die Spur-$\sigma$-[[zettel/Spur-σ-Algebra|Algebra]] $\overline{\mathscr{B}}_\mathbb{R}$
- $\overline{\mathscr{B}}_\mathbb{R} = \mathscr{B}$

---

Die Borelsche $\sigma$-[[zettel/σ-Algebra|Algebra]] ist [[zettel/σ-Algebra Invarianzen|translations-]] und [[zettel/σ-Algebra Invarianzen|spiegelungsinvariant]].
