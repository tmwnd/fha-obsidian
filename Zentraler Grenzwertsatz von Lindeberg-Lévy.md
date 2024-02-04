Seien $(X_n)_{n \in \mathbb{N}}$ [[Unabhängige Zufallsvariablen|unabhängige]], identisch verteilte, reele [[Zufallsvariable|Zufallsvariablen]] mit
- dem [[Erwartungswert]] $E[X_1] = 0$
- der [[Varianz]] $\text{Var}(X_1) = 1$
- $\forall n \in \mathbb{N} : S_n = \sum_{i=1}^n X_i$

Es gilt bzgl. der [[Verteilungskonvergenz]] und [[Normalverteilung]] $\mathcal{N}$

$$
	\forall n \in \mathbb{N} : \frac{1}{\sqrt{n}} S_n \stackrel{V}{\longrightarrow} \mathcal{N}(0, 1)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[Unabhängige Zufallsvariablen|unabhängige]] und identisch verteilte, reele [[Zufallsvariable|Zufallsvariablen]] mit
- dem [[Erwartungswert]] $\mu$ endlich
- der [[Varianz]] $\sigma^2$ endlich
- $\forall n \in \mathbb{N} : \overline{X}_n = \frac{1}{n} \sum_{i=1}^n X_i$

Es gilt bzgl. der [[Verteilungskonvergenz]] und [[Normalverteilung]] $\mathcal{N}$

$$
	\forall n \in \mathbb{N} : \sqrt{n} (\overline{X}_n - \mu) \stackrel{V}{\longrightarrow} \mathcal{N}(0, \sigma^2)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[Unabhängige Zufallsvariablen|unabhängige]] und identisch verteilte, reele [[Zufallsvariable|Zufallsvariablen]], $Z$ eine [[Zufallsvariable]] mit
- dem [[Erwartungswert]] $E[X]$ endlich
- der [[Varianz]] $\text{Var}(X) \gt 0$ und endlich

Es gilt bzgl. der [[Normalverteilung|Standardnormalverteilung]] $Z \sim \mathcal{N}(0, 1)$, falls
- $\sigma Z + \mu \sim \mathcal{N}(\mu, \sigma^2)$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[Unabhängige Zufallsvariablen|unabhängige]] und identisch verteilte, reele [[Zufallsvariable|Zufallsvariablen]] mit
- dem [[Erwartungswert]] $\mu$ endlich
- der [[Varianz]] $\sigma^2 = 0$

Es gilt
- $\forall i \in \mathbb{N} : X_i \equiv \mu$ fast sicher
- $\forall n \in \mathbb{N} : \sqrt{n}(\overline{X}_n - \mu)$ fast sicher