---
title: Zentraler Grenzwertsatz von Lindeberg-Lévy
type: theorem
---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable unabhängig|unabhängige]], identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- dem [[zettel/Zufallsvariable Erwartungswert|Erwartungswert]] $E[X_1] = 0$
- der [[zettel/Zufallsvariable Varianz|Varianz]] $\text{Var}(X_1) = 1$
- $\forall n \in \mathbb{N} : S_n = \sum_{i=1}^n X_i$

Es gilt bzgl. der [[zettel/Verteilungskonvergenz|Verteilungskonvergenz]] und [[zettel/Normalverteilung|Normalverteilung]] $\mathcal{N}$

$$
	\forall n \in \mathbb{N} : \frac{1}{\sqrt{n}} S_n \overset{V}{\longrightarrow} \mathcal{N}(0, 1)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable unabhängig|unabhängige]] und identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- dem [[zettel/Zufallsvariable Erwartungswert|Erwartungswert]] $\mu$ endlich
- der [[zettel/Zufallsvariable Varianz|Varianz]] $\sigma^2$ endlich
- $\forall n \in \mathbb{N} : \overline{X}_n = \frac{1}{n} \sum_{i=1}^n X_i$

Es gilt bzgl. der [[zettel/Verteilungskonvergenz|Verteilungskonvergenz]] und [[zettel/Normalverteilung|Normalverteilung]] $\mathcal{N}$

$$
	\forall n \in \mathbb{N} : \sqrt{n} (\overline{X}_n - \mu) \overset{V}{\longrightarrow} \mathcal{N}(0, \sigma^2)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable unabhängig|unabhängige]] und identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]], $Z$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit
- dem [[zettel/Zufallsvariable Erwartungswert|Erwartungswert]] $E[X]$ endlich
- der [[zettel/Zufallsvariable Varianz|Varianz]] $\text{Var}(X) \gt 0$ und endlich

$Z$ ist [[zettel/Normalverteilung|standardnormalverteilt]], falls
- $\sigma Z + \mu \sim \mathcal{N}(\mu, \sigma^2)$

---

Seien $(X_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable unabhängig|unabhängige]] und identisch verteilte, reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- dem [[zettel/Zufallsvariable Erwartungswert|Erwartungswert]] $\mu$ endlich
- der [[zettel/Zufallsvariable Varianz|Varianz]] $\text{Var}(X)  = 0$

Es gilt
- $\forall i \in \mathbb{N} : X_i \equiv \mu$ fast sicher
- $\forall n \in \mathbb{N} : \sqrt{n}(\overline{X}_n - \mu)$ fast sicher