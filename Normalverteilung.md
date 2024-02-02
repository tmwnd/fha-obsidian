Sei $\mu \in \mathbb{R}$, $\sigma^2 \in (0, \infty)$, $t \in \mathbb{R}$ und die  $\lambda$-[[lambda-Dichte|Dichte]] $\varphi_{\mu, \sigma^2}$ definiert als

$$
	\varphi_{\mu, \sigma^2}(t) = \frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{1}{2}\frac{(t-\mu)^2}{\sigma^2}}
$$

Sei $x \in \mathbb{R}$.

Die [[Verteilungsfunktion]] einer reelwertigen [[Zufallsvariable]] $X$ heißt *normalverteilt*, falls

$$
	F(x) = \int_{-\infty}^x \varphi_{\mu, \sigma^2}(t) dt
$$

Schreibe $X \sim \mathcal{N}(\mu, \sigma^2)$

---

Sei $X \sim \mathcal{N}(0, 1)$.

Die [[Verteilungsfunktion]] von $X$ heißt *Standardnormalverteilt*.

---

Sei $X \sim \mathcal{N}(\mu, \sigma^2)$ eine [[Zufallsvariable]].

Es gilt
- Der [[Erwartungswert]] ist $E[X] = \mu$
- Die [[Varianz]] ist $\text{Var}(X) = \sigma^2$