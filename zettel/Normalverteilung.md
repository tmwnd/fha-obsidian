---
title: Normalverteilung
type: example
---

Sei $\mu \in \mathbb{R}$, $\sigma^2 \in (0, \infty)$, $t \in \mathbb{R}$ und die  $\lambda$-[[zettel/λ-Dichte|Dichte]] $\varphi_{\mu, \sigma^2}$ definiert als

$$
	\varphi_{\mu, \sigma^2}(t) = \frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{1}{2}\frac{(t-\mu)^2}{\sigma^2}}
$$

Sei $x \in \mathbb{R}$.

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] einer reelwertigen [[zettel/Zufallsvariable|Zufallsvariable]] $X$ heißt *normalverteilt*, falls

$$
	F(x) = \int_{-\infty}^x \varphi_{\mu, \sigma^2}(t) dt
$$

Schreibe
- $X \sim \mathcal{N}(\mu, \sigma^2)$

---

Sei $X \sim \mathcal{N}(0, 1)$.

Die [[zettel/Verteilungsfunktion|Verteilungsfunktion]] von $X$ heißt *standardnormalverteilt*.

---

Sei $X \sim \mathcal{N}(\mu, \sigma^2)$ eine [[zettel/Zufallsvariable|Zufallsvariable]].

Es gilt
- Der [[zettel/Erwartungswert|Erwartungswert]] von $X$ ist $E[X] = \mu$
- Die [[zettel/Varianz|Varianz]] von $X$ ist $\text{Var}(X) = \sigma^2$

---

Sei $n \in \mathbb{N}$, $(X_i)_{i \in \{ 1, \dots, n \}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]] [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $X = (X_1, \dots, X_n)$
- $\forall i \in \{ 1, \dots, n \} : X_i \sim N(0, 1)$
- $x \in \mathbb{R}^n$

Die $\lambda^n$-[[zettel/λ-Dichte|Dichte]] $f$ von $X$ ist

$$
	f(x) = \left( \frac{1}{2\pi}^\frac{n}{2} \right) \cdot e^{-\frac{1}{2}|x|^n}
$$

Schreibe
- $X \sim \mathcal{N}_n(\vec{0}, I_n)$ mit
	- $\vec{0} \in \mathbb{R}^d$ dem Nullvektor
	- $I_n \in \mathbb{R}^{n \times n}$ der Einheitsmatrix

---

Sei $n \in \mathbb{N}$, $X \sim \mathcal{N}_n(\vec{0}, I_n)$ ein $n$-dimensional standardnormalverteilter [[zettel/Zufallsvariable|Zufallsvektor]], $A \in \mathbb{R}^{n \times n}$ regulär, $b \in \mathbb{R}^n$, $Y = AX + b$ mit
- $y \in \mathbb{R}^n$

Es gilt mit dem [[zettel/Erwartungswert|Erwartungswert]] $E$ und der [[zettel/Covarianz|Covarianz]] Cov
- $E[Y] = b$
- $\text{Cov}(Y) = \Sigma = AA^T$

Die $\lambda^n$-[[zettel/λ-Dichte|Dichte]] $f$ von $Y$ ist

$$
	f(y) = \left( \frac{1}{2\pi} \right)^\frac{n}{2} \cdot \frac{1}{\sqrt{\text{det}(\Sigma)}} \cdot e^{-\frac{1}{2} \cdot (y-b) \cdot \Sigma^{-1}(y-b)}
$$

$Y$ ist [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]], falls
- $\Sigma$ eine Diagonalmatrix ist

Schreibe
- $X \sim \mathcal{N}_n(b, \Sigma)$

---

Sei $n \in \mathbb{N}$, $X \sim \mathcal{N}_n(b, \Sigma)$ ein [[zettel/Zufallsvariable|Zufallsvektor]].

Es gilt
- Der [[zettel/Erwartungswert|Erwartungswert]] ist $E[X] = b$
- Die [[zettel/Varianz|Varianz]] ist $\text{Var}(X) = \Sigma$

---

Sei $X$ ein $d$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]], $\mu, z \in \mathbb{R}^d$, $\Sigma \in \mathbb{R}^{d \times d}$ eine symmetrisch, positiv semidifinite Matrix.

$X$ heißt *normalverteilt*, falls die [[zettel/Fourier-Transformierte|Fourier-Transformierte]] $\varphi_X$ definiert ist als

$$
	\varphi_X(z) = e^{i\mu^Tz-\frac{1}{2}z^T\Sigma z}
$$

---

Sei $X$ ein $d$-dimensionaler [[zettel/Zufallsvariable|Zufallsvektor]].

$X$ heißt *normalverteilt*, falls

$$
	\forall k \in \mathbb{R}^d : k^T X \sim \mathcal{N}(\vec{0}, I_d)
$$