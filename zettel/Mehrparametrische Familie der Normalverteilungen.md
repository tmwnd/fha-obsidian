Sei $\mu \in \mathbb{R}$, $\sigma^2 \in \mathbb{R}$ mit
- $\vartheta := \left( \frac{\mu}{\sigma^2}, -\frac{1}{2\sigma^2} \right)$

Die [[zettel/λ-Dichte|λ-Dichte]] von $\mathcal{N}(\mu, \sigma^2)$ kann geschrieben werden als

$$
	f(x, \vartheta) = \underbrace{\frac{1}{\sqrt{2\pi\sigma^2}} \cdot e^{-\frac{\mu^2}{2\sigma^2}}}_{c(\vartheta)} \cdot \underbrace{e^{\frac{\mu}{\sigma^2} \cdot x}}_{e^{\vartheta^T \cdot T(x)}} \cdot \underbrace{e^{-\frac{x^2}{2\sigma^2}}}_{h(x)} \quad x \gt 0
$$

mit
- $c(\vartheta) := \frac{1}{\sqrt{2\pi\sigma^2}} \cdot e^{-\frac{\mu^2}{2\sigma^2}} \mid \vartheta \in \Theta$
- $T(x) := (x, x^2)^T \mid x \gt 0$
- $h(x) := e^{-\frac{x^2}{2\sigma^2}} \mid x \gt 0$