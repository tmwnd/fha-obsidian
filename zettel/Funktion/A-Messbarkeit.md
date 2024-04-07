---
title: A-messbare Funktion
type: property
---

Sei $(\Omega, \mathcal{A})$ ein [[zettel/Messraum|Messraum]].

Die [[zettel/Funktion|Funktion]] $f : \Omega \to \mathbb{R}$ heißt *$\mathcal{A}$-messbar*, falls
- $\forall r \in \mathbb{R} : \{ \omega \in \Omega \mid f(\omega) \le r \} \in \mathcal{A}$

Schreibe
- $f \in \overline{Z(\Omega, \mathcal{A})}$

---

Sei $(\Omega, \mathcal{A})$ ein [[zettel/Messraum|Messraum]].

Die Mengen der $\mathcal{A}$-messbaren Funktionen ist definiert als
- $Z(\Omega, \mathcal{A}) := \{ f : (X, \mathcal{A}) \to (\mathbb{R}, \mathcal{L}) \mid f (\mathcal{A}, \mathcal{L})\text{-messbar} \}$
- $\overline{Z(\Omega, \mathcal{A})} := \{ f : (X, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L})} \mid f (\mathcal{A}, \overline{\mathcal{L}})\text{-messbar} \}$
- $Z_+(\Omega, \mathcal{A}) := \{ f : (X, \mathcal{A}) \to (\mathbb{R}, \mathcal{L}) \mid f (\mathcal{A}, \mathcal{L})\text{-messbar} \land f \ge 0 \}$
- $\overline{Z_+(\Omega, \mathcal{A})} := \{ f : (X, \mathcal{A}) \to (\overline{\mathbb{R}}, \overline{\mathcal{L})} \mid f (\mathcal{A}, \overline{\mathcal{L}})\text{-messbar} \land f \ge 0 \}$