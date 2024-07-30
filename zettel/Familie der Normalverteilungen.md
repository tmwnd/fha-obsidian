Sei $\sigma^2 \gt 0$ bekannt, $\mu \in \mathbb{R}$ mit
- $\vartheta := \frac{\mu}{\sigma^2} \in \mathbb{R}$

Die [[zettel/λ-Dichte|λ-Dichte]] von $\mathcal{N}(\mu, \sigma^2)$ kann geschrieben werden als

$$
	f(x, \vartheta) = \underbrace{\frac{1}{\sqrt{2\pi\sigma^2}} \cdot e^{-\frac{\mu}{2\sigma^2}}}_{c(\vartheta)} \cdot \underbrace{e^{\frac{\mu}{\sigma^2} \cdot x}}_{e^{\vartheta \cdot T(x)}} \cdot \underbrace{e^{-\frac{x^2}{2\sigma^2}}}_{h(x)} \quad x \gt 0
$$

mit
- $c(\vartheta) := \frac{1}{\sqrt{2\pi\sigma^2}} \cdot e^{-\frac{\mu}{2\sigma^2}} \quad \vartheta \in \Theta$
- $T(x) := x \quad x \gt 0$
- $h(x) := e^{-\frac{x^2}{2\sigma^2}} \quad x \gt 0$