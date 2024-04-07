---
title: Mehrdimensionaler zentraler Grenzwertsatz
type: definition
---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte, $d$-dimensionale [[zettel/Zufallsvariable|Zufallsvektoren]] mit
- dem [[zettel/Erwartungswert|Erwartungswert]] $\mu$
- der symmetrisch, postitv definiten [[zettel/Covarianz|Kovarianzmatrix]] $\Sigma$
- $\forall n \in \mathbb{N} : \overline{X}_n = \frac{1}{n} \sum_{i=1}^n X_i$

Es gilt bzgl. der [[zettel/Verteilungskonvergenz|Verteilungskonvergenz]] und der [[zettel/Normalverteilung|Normalverteilung]]

$$
	\forall n \in \mathbb{N} : \sqrt{n} (\overline{X}_n - \mu) \overset{V}{\longrightarrow} \mathcal{N}_d(\vec{0}, \Sigma)
$$