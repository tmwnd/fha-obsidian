---
title: Satz 6.8
type: theorem
---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $(X_n)_{n \in \mathbb{N}_0}$ reelle [[Zufallsvariable|Zufallsvariablen]] auf $(\Omega, \mathcal{A}, P)$ mit den [[Verteilungsfunktion|Verteilungsfunktionen]] $(F_n)_{n \in \mathbb{N}_0}$ mit
- $X_n \overset{V}{\longrightarrow} X_0$ [[Verteilungskonvergenz|verteilungskonvergent]]
- $C(F_0^{-1})$ der Menge der Stetigkeitspunkte von $F_0^{-1}$

Es gilt

$$
	\forall u \in C(F_0^{-1}) \cap (0, 1) : \lim_{n \to \infty} F_n^{-1}(u) = F_0^{-1}(0)
$$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $(X_n)_{n \in \mathbb{N}_0}$ reelle [[Zufallsvariable|Zufallsvariablen]] auf $(\Omega, \mathcal{A}, P)$, $(\tilde{\Omega}, \tilde{\mathcal{A}}, \tilde{P})$ ein beliebiger [[Wahrscheinlichkeitsraum]], $U \sim \mathcal{R}(0, 1)$ eine [[Gleichverteilung|gleichverteilte]] [[Zufallsvariable]] auf $(\tilde{\Omega}, \tilde{\mathcal{A}}, \tilde{P})$ mit
- $X_n \overset{V}{\longrightarrow} X_0$ [[Verteilungskonvergenz|verteilungskonvergent]]

Es gilt
- $F_n^{-1}(U) \overset{\tilde{P}\text{-f. s.}}{\longrightarrow} F_0^{-1}(U)$ $P$-[[Konvergenz P-fast sicher|f. s.]]
- $\forall n \in \mathbb{N}_0 : \tilde{P}^{F_n^{-1}(U)} = P^{X_n}$

---

Sei $(\Omega, \mathcal{A}, P)$ ein [[Wahrscheinlichkeitsraum]], $(X_n)_{n \in \mathbb{N}_0}$ reelle [[Zufallsvariable|Zufallsvariablen]] auf $(\Omega, \mathcal{A}, P)$, $(\tilde{\Omega}, \tilde{\mathcal{A}}, \tilde{P})$ ein beliebiger [[Wahrscheinlichkeitsraum]] mit
- $X_n \overset{V}{\longrightarrow} X_0$ [[Verteilungskonvergenz|verteilungskonvergent]]

Es existieren $(Y_n)_{n \in \mathbb{N}}$ [[Zufallsvariable|Zufallsvariablen]] auf $(\tilde{\Omega}, \tilde{\mathcal{A}}, \tilde{P})$ mit
- $\forall n \in \mathbb{N}_0 : \tilde{P}^{Y_n} = P^{X_n}$
- $Y_n \overset{\tilde{P}\text{-f. s.}}{\longrightarrow} Y_0$ $P$-[[Konvergenz P-fast sicher|f. s.]]