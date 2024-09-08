Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\forall n \in \mathbb{N} : S_n := \sum_{i=1}^n X_i$
- $\forall n \in \mathbb{N} : \mu := \text{E}[X_n]$
- $\forall n \in \mathbb{N} : 0 \lt \sigma^2 := \text{Var}[X_n] \lt \infty$

Es gilt

$$
	\lim_{n \to \infty} \frac{S_n - n\mu}{\sigma\sqrt{n}} \overset{V}{\longrightarrow} \mathcal{N}(0, 1)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\text{E}[X_1] = 0$
- $\text{Var}[X_1] = 1$
- $\forall n \in \mathbb{N} : S_n = \sum_{i=1}^n X_i$

Es gilt

$$
	\forall n \in \mathbb{N} : \frac{1}{\sqrt{n}} S_n \overset{V}{\longrightarrow} \mathcal{N}(0, 1)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\mu \lt \infty$
- $\sigma^2 \lt \infty$
- $\forall n \in \mathbb{N} : \overline{X}_n = \frac{1}{n} \sum_{i=1}^n X_i$

Es gilt

$$
	\forall n \in \mathbb{N} : \sqrt{n} (\overline{X}_n - \mu) \overset{V}{\longrightarrow} \mathcal{N}(0, \sigma^2)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $Z$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit
- $\text{E}[X] \lt \infty$
- $\text{Var}[X] \lt \infty$

$Z$ ist [[zettel/_examples/Normalverteilung|standardnormalverteilt]], falls
- $\sigma Z + \mu \sim \mathcal{N}(\mu, \sigma^2)$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\mu \lt \infty$
- $\text{Var}[X]  = 0$

Es gilt
- $\forall i \in \mathbb{N} : X_i \equiv \mu$ fast sicher
- $\forall n \in \mathbb{N} : \sqrt{n}(\overline{X}_n - \mu)$ fast sicher