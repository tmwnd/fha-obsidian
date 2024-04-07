---
title: Korollar 6.7
type: corollary
---

Seien $X, (X_n)_{n \in \mathbb{N}}$ $r$-dimensionale [[zettel/Zufallsvariable|Zufallsvektoren]], $(Y_n)_{n \in \mathbb{N}}$ $s$-dimensionale
[[zettel/Zufallsvariable|Zufallsvektoren]], $c \in \mathbb{R}^s$ mit
- $X_n \overset{V}{\longrightarrow} X$ [[zettel/Verteilungskonvergenz|verteilungskonvergent]]
- $Y_n \overset{P}{\longrightarrow} c$ [[zettel/Stochastische Konvergenz|stochastisch]] konvergent
- $r = s$

Es gilt nach [[zettel/Lemma von Slutsky|Slutsky]]
- $X_n + Y_n \overset{V}{\longrightarrow} X + c$ [[zettel/Verteilungskonvergenz|verteilungskonvergent]] und
- $Y_n^TX_n \overset{V}{\longrightarrow} c^TX$

---

Sei $c \in \mathbb{N}$, $X, (X_n)_{n \in \mathbb{N}}$ $r$-dimensionale [[zettel/Zufallsvariable|Zufallsvektoren]], $(Y_n)_{n \in \mathbb{N}}$ [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $X_n \overset{V}{\longrightarrow} X$ [[zettel/Verteilungskonvergenz|verteilungskonvergent]]
- $Y_n \overset{P}{\longrightarrow} c$ [[zettel/Stochastische Konvergenz|stochastisch]] konvergent
- $c \ne 0$

und

$$
	\forall n \in \mathbb{N}, \omega \in \mathbb{R} : Y_n(\omega) = 0 \implies \frac{1}{Y_n(\omega)}X_n(\omega) = 0
$$

Es gilt nach [[zettel/Lemma von Slutsky|Slutsky]]
- $\frac{1}{Y_n}X_n \overset{V}{\longrightarrow} \frac{1}{c}X$ [[zettel/Verteilungskonvergenz|verteilungskonvergent]]