---
title: Elementarfunktion
type: property
aliases:
  - elementare Funktion
  - primitive Funktion
  - einfache Funktion
---

Eine [[zettel/Funktion|Funktion]] $f : \Omega \to \mathbb{R}$ heißt *elementar*, falls
- endlich viele, paarweise verschiedene Werte $\alpha_1, \dots, \alpha_n$ angenommen werden

Sei $\mathcal{A}$ die $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $n \in \mathbb{N}$, $i \in \{ 1, \dots, n \}$, $A_i = \{ f = \alpha_i \} \subseteq \mathcal{A}$ geeignete p. d. Mengen und $I_{A_i}$ die [[zettel/Indikatorfunktion|Indikatorfunktion]] für $A_i$ mit
- $\bigcup_{i = 1}^n A_i = \Omega$

$f$ hat die *Normalenarstellung*

$$
	f = \sum_{i = 1}^n \alpha_i \cdot I_{A_i}
$$

---

Sei $(\Omega, \mathcal{A})$ ein [[zettel/Messraum|Messraum]].

Die Menge der *Elementarfunktionen* ist definiert als
- $E(X, \mathcal{A}) := \{ f \in Z(X, \mathcal{A}) \mid f(X) \text{ endlich} \}$