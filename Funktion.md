Sei $f$ eine *Funktion* mit
- dem Positivteil: $f^+ = \max(f, 0)$
- dem Negativteil. $f^- = \max(-f, 0)$

Es gilt
- $f = f^+ - f^-$

---

Eine Funktion $f : \mathcal{A} \to \mathcal{L}$ heißt *messbar*, falls
- $f$ $\mathcal{A}$-[[A-Messbarkeit|messbar]] ist oder
- $f$ $(\mathcal{A}, \mathcal{L})$-[[A-S-Messbarkeit|messbar]] ist oder
- $f$ $(\mathcal{A}, \overline{\mathcal{L}})$-[[A-S-Messbarkeit|messbar]] ist

Schreibe
- $f \in \mathcal{M}$

---

Seien $f, g$ messbare Funktionen und $a \in \overline{\mathbb{R}}$.

Folgende Funktionen sind messbar
- $a \cdot f$
- $f + g$
- $f \cdot g$
- $\frac{f}{g}$, falls definiert

Es gilt
- $f^+$, $f^-$ sind nicht-negative messbare Funktionen
- $|f| = f^+ + f^-$

---

Die Menge aller messbaren Funktionen ist mit der Borelschen $\sigma$-[[Borelsche sigma-Algebra|Algebra]] $\mathcal{L}$ definiert als

$$
	\mathcal{M} = \mathcal{M}(\Omega, \mathcal{A}) = \{ f, f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}}) \}
$$

Die Menge aller nicht-negativen messbaren Funktionen ist definiert als

$$
	\mathcal{M}_+ = \mathcal{M}_+(\Omega, \mathcal{A}) = \{ f, f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}}) \land f \ge 0 \}
$$

---

Seien $(\Omega, \mathcal{A}), (R, \mathcal{R}), (S, \mathscr{S})$ [[Messraum|Messräume]], $f : (\Omega, \mathcal{A}) \to (R, \mathcal{R})$ und $g : (R, \mathcal{R}) \to (S, \mathscr{S})$ messbare Funktion.

Die Funktion $f \circ g = g(f) : (\Omega, \mathcal{A}) \to (S, \mathscr{S})$ ist messbar,

---

Seien $(f_n)_{n \in \mathbb{N}}$ messbare Funktionen.

Die Funktionen $\sup_{n \in \mathbb{N}} f_n$ und $\inf_{n \in \mathbb{N}} f_n$ sind messbar.

---

Eine Funktion $f : \Omega \to \mathbb{R}$ heißt *primitiv*, falls
- endlich viele, paarweise verschiedene Werte $\alpha_1, \dots, \alpha_n$ angenommen werden

Sei $\mathcal{A}$ die $\sigma$-[[sigma-Algebra|Algebra]] auf $\Omega$, $n \in \mathbb{N}$, $i \in \{ 1, \dots, n \}$, $A_i = \{ f = \alpha_i \} \subseteq \mathcal{A}$ geeignete p. d. Mengen und $I_{A_i}$ die [[Indikatorfunktion]] für $A_i$ mit
- $\bigcup_{i = 1}^n A_i = \Omega$

$f$ hat die *Normalenarstellung*

$$
	f = \sum_{i = 1}^n \alpha_i \cdot I_{A_i}
$$

---

Den reellen Vektorraum der primitiven Funktionen auf dem [[Messraum]] $(\Omega, \mathcal{A})$ bezeichnen wir mit $\mathcal{P}(\Omega, \mathcal{A})$ bzw $\mathcal{P}$.

---

Sei $(\Omega, \mathcal{A}, \mu)$ ein [[Maßraum]], $N \in \mathcal{A}$ eine $\mu$-[[mu-Nullmengen|Nullmenge]], $\mathcal{L}$ die Borelsche $\sigma$-[[Borelsche sigma-Algebra|Algebra]]  mit

Eine Funktion $g$ ist *$\mu$-[[mu-Nullmengen|f. ü.]] definiert*, falls
- $g : (N^\complement, \mathcal{A}_{N^\complement}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}})$ $\mu$-[[mu-Integrierbarkeit|integrierbare]] ist
- $\tilde{g}(\omega) = \begin{cases} g(w), & \omega \in N^\complement \\ 0, & \omega \in N \end{cases}$ $\mu$-[[mu-Integrierbarkeit|integrierbare]] ist