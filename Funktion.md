Sei $f$ eine *Funktion* mit
- dem Positivteil: $f^+ = \max(f, 0)$
- dem Negativteil. $f^- = \max(-f, 0)$

Es gilt
- $f = f^+ - f^-$

Falls $f$ messbar
- $f^+$, $f^-$ sind nicht-negative messbare Funktionen
- $|f| = f^+ + f^-$

---

Eine Funktion $f : \mathcal{A} \to \mathcal{L}$ heißt *messbar*, falls
- $f$ $(\mathcal{A}, \mathcal{L})$-[[Lebesgue-Borelsches Maß|messbar]] ist oder
- $f$ $(\mathcal{A}, \overline{\mathcal{L}})$-[[Lebesgue-Borelsches Maß|messbar]] ist

---

Seien $f, g$ messbare Funktionen und $a \in \overline{\mathbb{R}}$.

Folgende Funktionen sind messbar
- $a \cdot f$
- $f + g$
- $f \cdot g$
- $\frac{f}{g}$, falls definiert

---

Seien $(\Omega, \mathcal{A}), (R, \mathcal{R}), (S, \mathscr{S})$ [[Messraum|Messräume]], $f : (\Omega, \mathcal{A}) \to (R, \mathcal{R})$ und $g : (R, \mathcal{R}) \to (S, \mathscr{S})$ messbare Funktion.

Die Funktion $f \circ g = g(f) : (\Omega, \mathcal{A}) \to (S, \mathscr{S})$ ist messbar, 

---

Seien $(f_n)_{n \in \mathbb{N}}$ messbare Funktionen.

Die Funktionen $\sup_{n \in \mathbb{N}} f_n$ und $\inf_{n \in \mathbb{N}} f_n$ sind messbar.

---

Eine Funktion $f : \Omega \to \mathbb{R}$ heißt *primitiv*, falls
- endlich viele, paarweise verschiedene Werte $\alpha_1, \dots, \alpha_n$ angenommen werden

Seien $\mathcal{A}$ die $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$, $i \in \{ 1, \dots, n \}$, $A_i = \{ f = \alpha_i \} \subseteq \mathcal{A}$ geeignete p. d. Mengen und $I_{A_i}$ die [[Indikatorfunktion]] für $A_i$ mit
- $\bigcup_{i = 1}^n A_i = \Omega$

$f$ hat die *Normalenarstellung*

$$
	f = \sum_{i = 1}^n \alpha_i \cdot I_{A_i}
$$

---

Den reelen Vektorraum der primitiven Funktionen auf dem [[Messraum]] $(\Omega, \mathcal{A})$ bezeichnen wir mit $\mathcal{P}(\Omega, \mathcal{A})$ bzw $\mathcal{P}$.