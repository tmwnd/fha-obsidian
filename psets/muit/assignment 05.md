---
type: assignment
---

1. Für Beliebige $y \in Y$ (bzw. $z \in Z$) gilt für den $y$-Schnitt (bzw. $z$-Schnitt) einer Menge $A \in \mathcal{B} \otimes \mathcal{C} : A_y \in \mathcal{C}$ (bzw. $A_z \in \mathcal{B}$).
	
	Sei $y \in Y$ beliebig.
	Definiere dann:
	
	$$
		\mathcal{F} := \{ A \subseteq Y \times Z \mid A_y \in \mathcal{C} \}
	$$
	
	Zeigen Sie, dass $\mathcal{F}$ in der Tat eine $\sigma$-Algebra ist.

^1

2. Sei $f : \mathbb{R}^2 \to \mathbb{R}^2$ eine stetige Funktion.
	Zeigen Sie: Dann ist $f$ Borel-messbar.
	
	*Anleitung*: Zeigen Sie zunächst, dass bei stetigen Funktionen Urbilder offener Mengen immer offen sind.

^2

3. Sei $f : \mathbb{R}^2 \to \mathbb{R}^2$, $f(x, y) = \frac{1}{1 + |x|y^2}$ und auf dem Messraum $(\mathbb{R}^2, \mathcal{B}_2^*)$ ein Maß definiert durch
	
	$$
		\mu(A) := \int_A f d\lambda^2 \quad \forall A \in \mathcal{B}_2^*
	$$
	
	1. Begründen Sie genau, warum es sich bei $\mu$ um ein Maß handelt.
	2. Sei $A = [0, 1]$ und $\mu_1$ bzw. $\mu_2$ die Marginalmaße von $\mu$.
		Berechnen Sie $\mu_1(A)$ und $\mu_2(A)$.

^3

4. Sei in $\mathbb{R}^n$ eine Hyperebene $H$ gegeben, die zu einer der Koordinatenebenen parallel liegen soll.
	Zeigen Sie: $\lambda^n(H) = 0$

^4

5. Seien $(Y, \mathcal{B}, \mu)$ und $(Z, \mathcal{C}, \nu)$ zwei $\sigma$-finite Maßräume, weiter $\mathcal{A} = \mathcal{B} \otimes \mathcal{C}$ und $\pi = \mu \otimes \nu$ das Produktmaß.
	Sei $A \subseteq Y \times Z$ eine $\pi$-Nullmenge.
	
	1. Zeigen Sie: Für alle $\mu$-fast alle $y \in Y$ ist der $y$-Schnitt $A_y \subseteq Z$ eine $\nu$-Nullmenge und für $\nu$-fast alle $z \in Z$ ist der $z$-Schnitt $A_z \subseteq Y$ eine $\mu$-Nullmenge.
	2. Obige Aussagen gelten nur fast überall.
		Funden Sie eine Nullmenge, für die nur fast alle $y$-Schnitte und auch nur fast alle $z$-Schnitte Nullmengen sind.

^5