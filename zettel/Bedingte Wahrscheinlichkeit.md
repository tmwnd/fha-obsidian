Sei $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $A, B \in \mathcal{A}$, $P$ ein [[zettel/Wahrscheinlichkeitsmaß|Wahrscheinlichkeitsmaß]] mit
- $P(B) \gt 0$

Die *bedingte Wahrscheinlichkeit* von $A$ unter $B$ ist definiert als

$$
	P(A \mid B) := \frac{P(A \cap B)}{P(B)}
$$

---

Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $B \in \mathscr{B}^p$.

$\text{E}[I_B(X) \mid Y]$ heißt *bedingte Wahrscheinlichkeit* von $X \in B$ unter $Y$.

Schreibe
- $P(X \in B \mid Y) = \text{E}[I_B(X) \mid Y]$

---

Seien $X : (\Omega, \mathcal{A}) \to (\mathbb{R}^p, \mathscr{B}^p)$, $Y : (\Omega, \mathcal{A}) \to (\mathbb{R}^d, \mathscr{B}^d)$ [[zettel/Zufallsvariable|Zufallsvektoren]], $B \in \mathscr{B}^p$, $y \in \mathbb{R}^d$.

$\text{E}[I_B(X) \mid Y=y]$ heißt *bedingte Wahrscheinlichkeit* von $X \in B$ unter $Y=y$.

Schreibe
- $P(X \in B \mid Y) = \text{E}[I_B(X) \mid Y=y]$