---
title: diskretes Wahrscheinlichkeitsmaß
type: definition
---

Sei $\Omega \ne \emptyset$, $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $\Omega$, $\{ \omega \} \in \mathcal{A}$.

Ein Wahrscheinlichkeitsmaß $P : \mathcal{A} \to \overline{\mathbb{R}}_+$ heißt *diskret*, falls für eine abzählbare Menge $\Omega_0 \subseteq \Omega$ gilt
- $P(\Omega_0) = 1$

und hat durch das [[zettel/Dirac-Maß|Dirac-Maß]] $\delta$ die Form

$$
	P = \sum_{\omega \in \Omega_0} P(\{ \omega \}) \delta_\omega
$$