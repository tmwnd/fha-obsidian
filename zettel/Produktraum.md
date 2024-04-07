---
title: Produktraum
type: definition
---

Sei $n \in \mathbb{N}$, $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$ [[zettel/Messraum|Messräume]], $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable unabhängig|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$.

Der *Produktraum* $(R, \mathscr{S}, P)$ ist definiert als [[zettel/Wahrscheinlichkeitsraum|Wahrscheinlichkeitsraum]] mit
- $P_i = P^{X_i}$ der [[zettel/Verteilungsfunktion|Verteilungsfunktion]] auf $(R_i, \mathscr{S}_i)$
- $R = \prod_{i=1}^n R_i$
- $\mathscr{S} = \bigotimes_{i=1}^n \mathscr{S}_i$ der Produkt-$\sigma$-[[zettel/Produkt-σ-Algebra|Algebra]] auf $((R_i, \mathscr{S}_i))_{i \in \{ 1, \dots, n \}}$
- $P = \bigotimes_{i=1}^n P_i$