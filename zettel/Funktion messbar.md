---
title: messbare Funktion
type: definition
---

Eine [[zettel/Funktion|Funktion]] $f : \mathcal{A} \to \mathcal{L}$ heißt *messbar*, falls
- $f$ $\mathcal{A}$-[[zettel/Funktion A-messbar|messbar]] ist oder
- $f$ $(\mathcal{A}, \mathcal{L})$-[[zettel/Funktion A-S-messbar|messbar]] ist oder
- $f$ $(\mathcal{A}, \overline{\mathcal{L}})$-[[zettel/Funktion A-S-messbar|messbar]] ist

Schreibe
- $f \in \mathcal{M}$

---

Seien $f, g$ messbare [[zettel/Funktion|Funktionen]] und $a \in \overline{\mathbb{R}}$.

Folgende [[zettel/Funktion|Funktionen]] sind messbar
- $a \cdot f$
- $f + g$
- $f \cdot g$
- $\frac{f}{g}$, falls definiert

Es gilt
- $f^+$, $f^-$ sind nicht-negative messbare [[zettel/Funktion|Funktionen]]
- $|f| = f^+ + f^-$

---

Die Menge aller messbaren [[zettel/Funktion|Funktionen]] ist mit der Borelschen $\sigma$-[[zettel/Borelsche σ-Algebra|Algebra]] $\mathcal{L}$ definiert als

$$
	\mathcal{M} = \mathcal{M}(\Omega, \mathcal{A}) = \{ f, f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}}) \}
$$

Die Menge aller nicht-negativen messbaren [[zettel/Funktion|Funktionen]] ist definiert als

$$
	\mathcal{M}_+ = \mathcal{M}_+(\Omega, \mathcal{A}) = \{ f, f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}}) \land f \ge 0 \}
$$

---

Seien $(\Omega, \mathcal{A}), (R, \mathcal{R}), (S, \mathscr{S})$ [[zettel/Messraum|Messräume]], $f : (\Omega, \mathcal{A}) \to (R, \mathcal{R})$ und $g : (R, \mathcal{R}) \to (S, \mathscr{S})$ messbare [[zettel/Funktion|Funktion]].

Die [[zettel/Funktion|Funktion]] $f \circ g = g(f) : (\Omega, \mathcal{A}) \to (S, \mathscr{S})$ ist messbar.

---

Seien $(f_n)_{n \in \mathbb{N}}$ messbare [[zettel/Funktion|Funktionen]].

Die [[zettel/Funktion|Funktionen]] $\sup_{n \in \mathbb{N}} f_n$ und $\inf_{n \in \mathbb{N}} f_n$ sind messbar.