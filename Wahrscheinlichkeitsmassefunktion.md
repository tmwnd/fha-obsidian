Sei $\Omega_0 \subseteq \Omega$  mit
- $\Omega_0$ abzählbar
- $\Omega_0 \ne \emptyset$

Eine [[Funktion]] $p : \Omega \to \mathbb{R}_+$ heißt *Wahrscheinlichkeitsmassefunktion*, falls
- $\forall \omega \in \Omega_0^C : p(\omega) = 0$
- $\sum_{\omega \in \Omega} p(\omega) = \sum_{\omega \in \Omega_0} p(\omega) = 1$

---

Sei $p$ eine Wahrscheinlichkeitsmassefunktion.

Das [[Maß|Wahrscheinlichkeitsmaß]] $P$ auf $(\Omega, \mathcal{P}(\Omega))$ ist $p$ fest zugeordnet, eindeutig und es gilt
- $\forall \omega \in \Omega : P(\{ \omega \}) = p(\omega)$