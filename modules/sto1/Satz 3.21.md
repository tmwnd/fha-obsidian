---
title: Satz 3.21
type: theorem
---

Sei $\emptyset \ne G \subseteq \mathbb{R}^d$ offen und $\Phi : G \to \mathbb{R}^d$ eine geeignete $(\mathcal{L}^d, \mathcal{L}^d)$-[[Funktion A-S-messbar|messbare]] Transformation, $\Delta : \mathbb{R}^d \to \mathbb{R}$ die [[Funktionaldeterminante]] und $f : (\Phi(G), \mathcal{L}_{\Phi(G)}^d) \to (\mathbb{R}, \mathcal{L})$ eine nicht-negative [[Funktion]] mit
- $\Phi$ injektiv
- $\Phi$ stetig differenzierbar
- $\Delta$ verschwindet nirgends

Es gilt für die $\lambda^d$-Dichte

$$
	\int_{\Phi(G)} f(y) dy = \int_G f \circ \Phi(x) \cdot |\Delta(x)| dx
$$