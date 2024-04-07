---
title: Äußeres Lebesgue-Maß
type: example
---

Sei $A \subseteq \Omega$, $\mathcal{C}(A) = \{ ((a_n, b_n])_{n \in \mathbb{N}} \mid \forall n \in \mathbb{N} : a_n \le b_n, A \subseteq \bigcup_{n \in \mathbb{N}} (a_n, b_n] \}$

Das *äußere Lebesgue-Maß* $\lambda^*$ ist definiert als

$$
	\lambda^*(A) = \inf\left\{ \sum_{n \in \mathbb{N}} b_n - a_n \mid ((a_n, b_n])_{n \in \mathbb{N}} \in \mathcal{C}(A) \right\}
$$