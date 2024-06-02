---
type: assignment
---

1. Es sei $X = (X_1, \dots, X_n)$ mit unabhängigen Zufallsvariablen $X_1, \dots, X_n$, je mit derselben Verteilung
	
	$$
		P_\vartheta(X_1 = k) = \frac{1}{\vartheta} \quad \text{für } k \in \{ 1, \dots, \vartheta \}
	$$
	
	wobei $\vartheta \in \mathbb{N}$ unbekannt ist.
	
	1. Bestimmen Sie die Verteilung des Schätzers $M = \max_{1 \le \nu \le n} X_\nu$ für $\vartheta$.
	2. Zeigen Sie, dass
		
		$$
			d(M) = \frac{M^{n+1} - (M - 1)^{n+1}}{M^n - (M - 1)^n}
		$$
		
		ein gleichmäßig bester erwartungstreuer Schätzer für $\vartheta$ ist.
	
	*Hinweis*: Überlegen Sie sich, dass für jede Funktion $d : \mathbb{N}^n \to \mathbb{R}$, für die für jedes $\vartheta \in \mathbb{N}$
	
	$$
		\sum_{x_1=1}^\vartheta \dots \sum_{x_n=1}^\vartheta d(x_1, \dots, x_n) = 0
	$$
	
	ist, folgt, dass für jedes $t \in \mathbb{N}$
	
	$$
		\sum_{(x_1, \dots, x_n) \in \mathbb{N}^n, \max_{1 \le \nu \le n} x_\nu = t} d(x_1, \dots, x_n) = 0
	$$
	
	ist, und wenden Sie das Kovarianzkriterium von Rao an.

^1

2. Überprüfen Sie, ob es sich bei den folgenden Verteilungsfamilien um einparametrische Exponentialfamilien handelt.
	1. Die Familie der Normal-Verteilungen $\{ N(\mu, \sigma^2); \sigma^2 \in (0, \infty) \}$, mit $\mu \in \mathbb{R}$ fest.
	2. Die Familie der Gamma-Verteilungen $\{ G(\alpha, \lambda); \alpha \in (0, \infty) \}$, mit $\lambda \in (0, \infty)$ fest.
	3. Die Familie der Gamma-Verteilungen $\{ G(\alpha, \lambda); \lambda \in (0, \infty) \}$, mit $\alpha \in (0, \infty)$ fest.
	4. Die Familie der Binomial-Verteilungen $\{ \mathfrak{B}(n, p); p \in (0, 1) \}$, mit $n \in \mathbb{N}$ fest.
	5. Die Familie der Binomial-Verteilungen $\{ \mathfrak{B}(n, p); p \in \mathbb{N} \}$, mit $n \in (0, 1)$ fest.
	6. Die Familie der Poisson-Verteilungen $\{ \mathfrak{P}(\lambda); \lambda \in (0, \infty) \}$.
	7. Die Familie der negativen Binomial-Verteilungen auf $\mathbb{N}_0$ $\{ Nb(r, p); p \in (0, 1) \}$, mit $r \in \mathbb{N}$ fest.
	7. Die Familie der negativen Binomial-Verteilungen auf $\mathbb{N}_0$ $\{ Nb(r, p); r \in \mathbb{N} \}$, mit $p \in (0, 1)$ fest.
	8. Die Familie der diskreten Gleichverteilungen $\{ U\{ 1, \dots, a \}; a \in \mathbb{N} \}$.
	9. Die Familie der stetigen Gleichverteilungen $\{ U(0, a); a \in (0, \infty) \}$.

^2