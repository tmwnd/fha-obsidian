---
title: Stetigkeitssatz für die Fourier-Transformierte
type: theorem
---

Seien $X, (X_n)_{n \in \mathbb{N}}$ $d$-dimensionale [[zettel/Zufallsvariable|Zufallsvektoren]] mit den [[zettel/Fourier-Transformierte|Fourier-Transformierten]] $\varphi, (\varphi_n)_{n \in \mathbb{N}}$ mit
- $X_n \overset{V}{\longrightarrow} X$ [[zettel/Verteilungskonvergenz|verteilungskonvergent]]

Es gilt

$$
	\forall z \in \mathbb{R}^d : \lim_{n \to \infty} \varphi_n(z) = \varphi(z)
$$

---

Seien $(X_n)_{n \in \mathbb{N}}$ $d$-dimensionale [[zettel/Zufallsvariable|Zufallsvektoren]] mit den [[zettel/Fourier-Transformierte|Fourier-Transformierten]] $(\varphi_n)_{n \in \mathbb{N}}$, $\varphi : \mathbb{R}^d \to \mathbb{C}$ mit
- $\varphi$ ist stetig in $\vec{0}$
- $\forall z \in \mathbb{R}^d : \lim_{n \to \infty} \varphi_n(z) = \varphi(z)$

$\varphi$ ist die [[zettel/Fourier-Transformierte|Fourier-Transformierte]] eines [[zettel/Zufallsvariable|Zufallvektors]] $X^*$ und es gilt
- $X_n \overset{V}{\longrightarrow} X^*$ [[zettel/Verteilungskonvergenz|verteilungskonvergiert]]