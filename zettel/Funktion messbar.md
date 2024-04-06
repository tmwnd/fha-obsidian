---
title: messbare Funktion
type: definition
---

Eine [[Funktion]] $f : \mathcal{A} \to \mathcal{L}$ heißt *messbar*, falls
- $f$ $\mathcal{A}$-[[Funktion A-messbar|messbar]] ist oder
- $f$ $(\mathcal{A}, \mathcal{L})$-[[Funktion A-S-messbar|messbar]] ist oder
- $f$ $(\mathcal{A}, \overline{\mathcal{L}})$-[[Funktion A-S-messbar|messbar]] ist

Schreibe
- $f \in \mathcal{M}$

---

Seien $f, g$ messbare [[Funktion|Funktionen]] und $a \in \overline{\mathbb{R}}$.

Folgende [[Funktion|Funktionen]] sind messbar
- $a \cdot f$
- $f + g$
- $f \cdot g$
- $\frac{f}{g}$, falls definiert

Es gilt
- $f^+$, $f^-$ sind nicht-negative messbare [[Funktion|Funktionen]]
- $|f| = f^+ + f^-$

---

Die Menge aller messbaren [[Funktion|Funktionen]] ist mit der Borelschen $\sigma$-[[Borelsche σ-Algebra|Algebra]] $\mathcal{L}$ definiert als

$$
	\mathcal{M} = \mathcal{M}(\Omega, \mathcal{A}) = \{ f, f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}}) \}
$$

Die Menge aller nicht-negativen messbaren [[Funktion|Funktionen]] ist definiert als

$$
	\mathcal{M}_+ = \mathcal{M}_+(\Omega, \mathcal{A}) = \{ f, f : (\Omega, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L}}) \land f \ge 0 \}
$$

---

Seien $(\Omega, \mathcal{A}), (R, \mathcal{R}), (S, \mathscr{S})$ [[Messraum|Messräume]], $f : (\Omega, \mathcal{A}) \to (R, \mathcal{R})$ und $g : (R, \mathcal{R}) \to (S, \mathscr{S})$ messbare [[Funktion]].

Die [[Funktion]] $f \circ g = g(f) : (\Omega, \mathcal{A}) \to (S, \mathscr{S})$ ist messbar.

---

Seien $(f_n)_{n \in \mathbb{N}}$ messbare [[Funktion|Funktionen]].

Die [[Funktion|Funktionen]] $\sup_{n \in \mathbb{N}} f_n$ und $\inf_{n \in \mathbb{N}} f_n$ sind messbar.