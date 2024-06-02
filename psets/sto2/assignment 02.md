---
type: assignment
---

1. Für jedes $n \in \mathbb{N}$ seien $X_{n1}, \dots, X_{nn}$ unabhängig und identisch verteilte reelle Zufallsvariablen, je mit derselben Verteilung $Q_n$ mit $\int x^2 dQ_n(x) \lt \infty$ und $\int x dQ_n(x) = 0$ sowie $\sigma_n^2 = \int x^2 dQ_n(x) \gt 0$.
	Es sei $Q$ ein Wahrscheinlichkeitsmaß auf $(\mathbb{R}, \mathcal{B})$ mit $\int x^2 dQ(x) \lt \infty$ unt $\int x dQ(x) = 0$ sowie $\sigma^2 = \int x^2 dQ(x) \gt 0$.
	Es gelte $Q_n \leadsto Q$ und $\lim_{n \to \infty} \int x^2 dQ_n(x) = \int x^2 dQ(x) \lt \infty$.
	Zeigen Sie:
	
	$$
		\frac{\sum_{k=1}^n X_{nk}}{\sqrt{n}\sigma_n} \overset{v}{\longrightarrow} N(0, 1)
	$$
	
	*Hinweis*: Weisen Sie die Lindeberg-Bedingung nach.

^1

2. Gegeben sei ein Dreiecksschema $X_{n1}, \dots, X_{nr_n}$ von unabhängigen Zufallsvariablen für alle $n \in \mathbb{N}$, je mit derselben Verteilung $F_n$ mit $F_n \leadsto F$.
	Ferner gelte für alle $n \in \mathbb{N}$ $\int |x| dF_n(x)$, $\int |x| df(x) \lt \infty$ und es gelte $\int |x| df_n(x) \to \int |x| dF(x)$ und $r_n \to \infty$ für $n \to \infty$.
	Dann gilt auch mit $\mu := \int x dF(x)$
	
	$$
		\frac{1}{r_n} \sum_{k=1}^{r_n} X_{nk} \to \mu
	$$
	
	stochastisch für $n \to \infty$.
	
	*Hinweis*: Verwenden Sie Fourier-Transformierte.

^2