Seien $X, (X_n)_{n \in \mathbb{N}}$ $r$-dimensionale [[Zufallsvariable|Zufallsvektoren]], $(Y_n)_{n \in \mathbb{N}}$ $s$-dimensionale
[[Zufallsvariable|Zufallsvektoren]], $c \in \mathbb{R}^s$ mit
- $X_n \overset{V}{\longrightarrow} X$ [[Verteilungskonvergenz|verteilungskonvergent]]
- $Y_n \overset{P}{\longrightarrow} c$ [[Stochastische Konvergenz|stochastisch]] konvergent
- $r = s$

Es gilt nach [[Lemma von Slutsky|Slutsky]]
- $X_n + Y_n \overset{V}{\longrightarrow} X + c$ [[Verteilungskonvergenz|verteilungskonvergent]] und
- $Y_n^TX_n \overset{V}{\longrightarrow} c^TX$

---

Sei $c \in \mathbb{N}$, $X, (X_n)_{n \in \mathbb{N}}$ $r$-dimensionale [[Zufallsvariable|Zufallsvektoren]], $(Y_n)_{n \in \mathbb{N}}$ [[Zufallsvariable|Zufallsvariablen]] mit
- $X_n \overset{V}{\longrightarrow} X$ [[Verteilungskonvergenz|verteilungskonvergent]]
- $Y_n \overset{P}{\longrightarrow} c$ [[Stochastische Konvergenz|stochastisch]] konvergent
- $c \ne 0$

und

$$
	\forall n \in \mathbb{N}, \omega \in \mathbb{R} : Y_n(\omega) = 0 \implies \frac{1}{Y_n(\omega)}X_n(\omega) = 0
$$

Es gilt nach [[Lemma von Slutsky|Slutsky]]
- $\frac{1}{Y_n}X_n \overset{V}{\longrightarrow} \frac{1}{c}X$ [[Verteilungskonvergenz|verteilungskonvergent]]