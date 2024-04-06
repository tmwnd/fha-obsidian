---
title: Stochastische Konvergenz
type: definition
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $X, (X_n)_{n \in \mathbb{N}}$ [[Zufallsvariable|Zufallsvariablen]].

Die Folge $(X_i)_{i \in \{ 1, \dots, n \}}$ *konvergiert stochastisch* bzw. *in Wahrscheinlichkeit* gegen $X$, falls

$$
	\forall \varepsilon \gt 0 : \lim_{n \to \infty} P(|X_n - X| \gt \varepsilon) = 0
$$

Schreibe
- $X_n \overset{P}{\longrightarrow} X$.

---

Aus $X_n \overset{P\text{-f. s.}}{\longrightarrow} X$ $P$-[[Konvergenz P-fast sicher|f. s.]] folgt $X_n \overset{P}{\longrightarrow} X$.

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $X, (X_n)_{n \in \mathbb{N}}$ [[Zufallsvariable|Zufallsvariablen]] mit
- $X_n \overset{P}{\longrightarrow} X$ konvergiert stochastisch

Es existiert eine Teilfolge $(X_{n_k})_{k \in \mathbb{N}} \subseteq (X_n)_{n \in \mathbb{N}}$ mit $P$-[[Konvergenz P-fast sicher|f. s.]]
- $X_{n_k} \overset{P\text{-f. s.}}{\longrightarrow} X$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $X, (X_n)_{n \in \mathbb{N}}$ [[Zufallsvariable|Zufallsvariablen]] mit $P$-[[Konvergenz P-fast sicher|f. s.]]
- $\forall (X_{n'})_{n' \in \mathbb{N}} \subseteq (X_n)_{n \in \mathbb{N}}, \exists (X_{n''})_{n'' \in \mathbb{N}} \subseteq (X_{n'})_{n' \in \mathbb{N}} : X_{n''} \overset{P\text{-f. s.}}{\longrightarrow} X$

Es gilt
- $X_n \overset{P}{\longrightarrow} X$

---

Sei $d, m \in \mathbb{N}$, $X, (X_n)_{n \in \mathbb{N}}$ [[Zufallsvariable|Zufallsvariablen]], $f : \mathbb{R}^d \to \mathbb{R}^m$ $P$-fast sicher stetig.

$f \circ X_n \overset{P}{\longrightarrow} f \circ X$ gilt falls
- $X_n \overset{P}{\longrightarrow} X$


---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $X, (X_n)_{n \in \mathbb{N}}$ $d$-dimensionale [[Zufallsvariable|Zufallsvektoren]], $Y, (Y_n)_{n \in \mathbb{N}}$ $m$-dimensionale [[Zufallsvariable|Zufallsvektoren]] mit
- $X_n \overset{P}{\longrightarrow} X$
- $Y_n \overset{P}{\longrightarrow} Y$

Es gilt

$$
	(X_n, Y_n) \overset{P}{\longrightarrow} (X, Y)
$$