---
title: Cauchy-Verteilung
type: example
---

Sei $\mu \in \mathbb{R}$, $\sigma \gt 0$, $t \in \mathbb{R}$ und die $\lambda$-[[λ-Dichte|Dichte]] $c_{\mu, \sigma}$ definiert als

$$
	c_{\mu, \sigma}(t) = \frac{\sigma}{\pi}\frac{1}{\sigma^2 + (x - \mu)^2}
$$

Sei $x \in \mathbb{R}$.

Die [[Verteilungsfunktion]] einer reelwertigen [[Zufallsvariable]] $X$ heißt *Cauchy-verteilt*, falls

$$
	F(x) = P(X \le x) = \int_{-\infty}^x x_{\mu, \sigma}(t) dt = \frac{1}{2} + \frac{1}{\pi}\arctan\left( \frac{x - \mu}{\sigma} \right)
$$

Schreibe
- $X \sim \mathcal{C}(\mu, \sigma)$