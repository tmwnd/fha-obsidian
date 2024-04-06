---
type: assignment
---

1. Beweisen Sie für das Mengensystem $\mathcal{I}^2$ folgende Aussagen:
	1. $\emptyset \in \mathcal{I}^2$
	2. $\mathcal{I}^2$ ist $\cap$-stabil
	3. $A, B \in \mathcal{I}^2 \implies A \setminus B \in (\mathcal{I}^2)^+$

^1

2. Sei $X \ne \emptyset$ und $\mathcal{A}$ eine $\sigma$-Algebra auf $X$.
	Beweisen Sie:
	
	$$
		\forall (A_n)_{n \in \mathbb{N}} \subseteq \mathcal{A} : \bigcap_{n = 1}^\infty A_n \in \mathcal{A}
	$$

^2

3. Sei $X \ne \emptyset$.
	Zeigen Sie, dass das Mengensystem
	
	$$
		\mathcal{A} := \{ A \subseteq X \mid A \lor A^\complement \text{ abzählbar } \}
	$$
	
	eine $\sigma$-Algebra ist.

^3

4. Sei $X \ne \emptyset$ und $\mathcal{D}$ ein Dynkinsystem auf $X$.
	Beweisen Sie:
	
	$$
		\forall A, B \in \mathcal{D} : A \subset B \implies B \setminus A \in \mathcal{D}
	$$

^4

5. Gegeben sei eine Funktion $f : X \to Y$ und eine $\sigma$-Algebra $\mathcal{B}$ auf $Y$.
	Zeigen Sie, dass $\mathcal{A} := f^{-1}(\mathcal{B})$ eine $\sigma$-Algebra auf $X$ ist.

^5

6. Beweisen Sie.
	
	Sei $X \ne \emptyset$ und $(\mathcal{A}_i)_{i \in I}$, mit $I \ne \emptyset$, ein indiziertes System von $\sigma$-Algebren (bzw. Dynkinsystemen) auf $X$.
	Dann gilt: $\mathcal{A} := \bigcap_{i \in I} \mathcal{A}_i$ ist wieder eine $\sigma$-Algebra (bzw. Dynkinsystem).

^6

7. Sei $X \ne \emptyset$ und $\mathcal{E}$ ein $\cap$-stabiles Mengensystem auf $X$.
	
	Beweisen Sie, dass die folgenden Mengensystem Dynkinsysteme sind:
	$$
		\forall D \in \delta(\mathcal{E}) : \mathcal{D}_D := \{ F \subseteq X \mid F \cap D \in \delta(\mathcal{E}) \}
	$$

^7

8. Beweisen Sie.
	
	Sei $\mathbb{R}^k$, für $k \ge 1$, versehen mit der üblichen Metrik im $\mathbb{R}^k$.
	Dann gilt:
	
	$$
		\mathcal{B}_k^* \equiv \mathcal{B}(\mathbb{R}^k) = \sigma(\mathcal{F}(\mathbb{R}^k)) = \sigma(\mathcal{I}^k) = \sigma(\mathcal{K}(\mathbb{R}^k))
	$$
	
	*Hinweis*: Beweisen Sie zunächst, dass jede offene Teilmenge von $\mathbb{R}^k$ eine abzählbare Vereinigung offener Intervalle mit rationalen Intervallgrenzen ist und nutzen Sie dies, um $\mathcal{B}_k^* \subseteq \sigma(\mathcal{I}^k)$ zu zeigen.

^8

9. Sei $(X, \mathcal{A}, \mu)$ ein Maßraum, $A, B \in \mathcal{A}$ mit $A \subseteq B$ und $\mu(A) \lt \infty$.
	Zeigen Sie: $\mu(B \setminus A) = \mu(B) - \mu(A)$.
	Warum muss hier $\mu(A) \lt \infty$ gefordert werden?

^9

10. Sei $X \ne \emptyset$ und $\mathcal{E} \subseteq \mathcal{P}(X)$ ein $\cap$-stabiler Erzeuger von $\mathcal{A} = \sigma(\mathcal{E})$, der eine wachsende Folge $(E_n)_{n \in \mathbb{N}} \subseteq \mathcal{E}$ enthält mit $E_n \uparrow X$.
	Sind dann $\mu_i$, für $i = 1, 2$, zwei Maße auf $(X, \mathcal{A})$ mit den Eigenschaften
	1. $\forall E \in \mathcal{E} : \mu_1(E) = \mu_2(E)$
	2. $\forall n \in \mathbb{N} : \mu_1(E_n) = \mu_2(E_n) \lt \infty$.
	
	Zeigen Sie, dass folgende Mengensysteme Dynkinsysteme sind, die zusätzlich noch jeweils den Erzeuger $\mathcal{E}$ enthalten.
	$$
		\mathcal{D}_n := \{ A \in \mathcal{A} \mid \mu_1(A \cap E_n) = \mu_2(A \cap E_n) \}, \quad \text{ für } n \in \mathbb{N}
	$$

^10

11. Sei $(X, \mathcal{A}, \mu)$ ein finiter Maßraum.
	Zeigen Sie:
	1. $\forall A, B \in \mathcal{A} : \mu(A \cup B) = \mu(A) + \mu(B) - \mu(A \cap B)$
	2. $\forall A, B, C \in \mathcal{A} : \mu(A \cup B \cup C) = \mu(A) + \mu(B) + \mu(C) - \mu(A \cap B) - \mu(A \cap C) - \mu(B \cap C) + \mu(A \cap B \cap C)$

^11

12. Sei $(X, \mathcal{A}, \mu)$ ein endlicher Maßraum.
	Zeigen Sie, dass für durch $d(A, B) : \mu(A \bigtriangleup B)$ eine Pseudometrik auf $\mathcal{A}$ definiert wird, d. h. $\forall A, B, C \in \mathcal{A} : d(A, A) = 0, d(A, B) = d(B, A), d(A, B) \le d(A, C) + d(C, B)$.
	Hierbei steht $A \bigtriangleup B := (A \setminus B) \cup (B \setminus A)$ für die *symmetrische Differenz* zweier Mengen.
	
	*Anleitung zur Dreiecksungleichung*: Zeigen Sie zunächst $A \bigtriangleup A = \emptyset$ sowie $A \bigtriangleup \emptyset = A$ für jede Menge $A$.
	Nutzen Sie dann die Assoziativität der symmetrischen Differenz, um $A \bigtriangleup B = (A \bigtriangleup C) \bigtriangleup (C \bigtriangleup B)$ zu zeigen.

^12

13. Sei $\mu$ das Zählmaß auf $(\mathbb{N}, \mathcal{P}(\mathbb{N}))$.
	Bestimmen Sie eine Folge $(A_n)_{n \in \mathbb{N}} \subseteq \mathcal{P}(\mathbb{N})$ mit der Eigenschaft: $A_n \downarrow A$ und $\mu(A) \ne \lim_{n \to \infty} \mu(A_n)$.
	
	Vergleichen Sie Ihr Ergebnis mit der $\sigma$-Stetigkeit eines Maßes von oben.

^13

14. Gegeben Seien ein Maßraum $(X, \mathcal{A}, \mu)$ und eine Menge $B \in \mathcal{A}$.
	Zeigen Sie, dass dann durch
	
	$$
		\nu(A) := \mu(A \cap B), \quad A \in \mathcal{A}
	$$
	
	ein neuer Maßraum $(X, \mathcal{A}, \nu)$ definiert wird.

^14

15. Es seien $(X, \mathcal{A}, \mu_i)$, $i = 1, \dots, n$ Maßräume und $a_1, \dots, a_n$ nicht-negative reele Zahlen, mit $n \in \mathbb{N}$.
	Zeigen Sie, dass durch
	
	$$
		\nu(A) := \sum_{i=1}^n a_i\mu_i(A), \quad A \in \mathcal{A}
	$$
	
	ein neuer Maßraum $(X, \mathcal{A}, \nu)$ definiert wird.

^15

16. Es seien $(\mu_n)_{n=1}^\infty$ Wahrscheinlichkeitsmaße auf $(X, \mathcal{A})$.
	Zeigen Sie, dass durch
	
	$$
		\nu(A) := \sum_{n=1}^\infty 2^{-n}\mu_n(A), \quad A \in \mathcal{A}
	$$
	
	ein neues Wahrscheinlichkeitsmaß $\nu$ auf $(X, \mathcal{A})$ definiert wird.

^16

17. Gegeben seien der messbare Raum $(\mathbb{N}, \mathcal{P}(\mathbb{N}))$ und eine Folge $(a_n)_{n \in \mathbb{N}}$ nicht-negativer reeller Zahlen.
	Zeigen Sie, dass durch
	
	$$
		\mu(\emptyset) := 0, \quad \mu(A) := \sum_{n \in A} a_n, \quad A \subseteq \mathbb{N}
	$$
	
	ein Maß auf $(\mathbb{N}, \mathcal{P}(\mathbb{N}))$ definiert wird.

^17