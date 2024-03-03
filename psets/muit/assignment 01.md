1. Beweisen Sie.
	
	Gegeben Sei $X \ne \emptyset$ und $\mathcal{A}, \mathcal{B} \subseteq \mathcal{P}(X)$ zwei indizierte Mengensysteme mit $\mathcal{A} = (A_i)_{i \in I}$ bzw. $\mathcal{B} = (B_i)_{j \in J}$.
	Ferner seien $A, B \subseteq X$ beliebige Teilmengen von $X$.
	
	Dann gilt:
	1. Komplementbildung
	
	$$
		(A^C)^C = A, \quad X^C = \emptyset, \quad \emptyset^C = X, \quad A \subseteq B \iff B^C \subseteq A^C
	$$
	
	2. De Morgansche Gesetze
	
	$$
		\left( \bigcup_{i \in I} A_i \right)^C = \bigcap_{i \in I}(A_i^C)
	$$
	
	$$
		\left( \bigcap_{i \in I} A_i \right)^C = \bigcup_{i \in I}(A_i^C)
	$$
	
	3. Distributivgesetz
	
	$$
		\left( \bigcup_{i \in I} A_i \right) \cap \left( \bigcup_{j \in J} B_j \right) = \bigcup_{i \in I}\bigcup_{j \in J}(A_i \cap B_j)
	$$
	
	$$
		\left( \bigcap_{i \in I} A_i \right) \cup \left( \bigcap_{j \in J} B_j \right) = \bigcap_{i \in I}\bigcap_{j \in J}(A_i \cup B_j)
	$$

^1

2. Sei $(A_n)_{n \in \mathbb{N}}$ ein indiziertes System von Teilmengen einer Menge $X$.
	Interpretieren Sie die Ausdrücke $\liminf_{n \to \infty} A_n$ und $\limsup_{n \to \infty} A_n$.

^2

3. Gegeben seien die Mengensysteme $(A_n)_{n \in \mathbb{N}}$ und $(B_n)_{n \in \mathbb{N}}$ mit $A_n := [0, 1 + \frac{1}{n})$ bzw. $B_n := [0, 1 - \frac{1}{n}]$, für $n \in \mathbb{N}$.
	Bestimmen Sie limes inferior und limes superior zu beiden Systemen.

^3

4. Gegeben sei eine Funktion $f : X \to Y$.
	Beweisen Sie:
	1. $\forall  B \subseteq Y : f^{-1}(Y \setminus B) = X \setminus f^{-1}(B)$
	2. $\forall B_1, B_2 \subseteq Y : B_1 \cap B_2 = \emptyset \implies f^{-1}(B_1) \cap f^{-1}(B_2) = \emptyset$
	3. $\forall A \subseteq X : A \subseteq f^{-1}(f(A))$
	4. $\forall B \subseteq Y : f(f^{-1}(B)) \subseteq B$

^4

5. Gegeben sei eine Funktion $f : X \to Y$ und $(A_i)_{i \in I} \subseteq \mathcal{P}(X)$ bzw. $(B_i)_{i \in I} \subseteq \mathcal{P}(Y)$ indizierte Mengensysteme.
	Beweisen Sie die folgenden Aussagen:
	1. $f(\bigcup_{i \in I} A_i) = \bigcup_{i \in I} f(A_i)$
	2. $f(\bigcap_{i \in I} A_i) \subseteq \bigcap_{i \in I} f(A_i)$
	3. $f^{-1}(\bigcup_{i \in I} B_i) = \bigcup_{i \in I} f^{-1}(B_i)$
	3. $f^{-1}(\bigcap_{i \in I} B_i) = \bigcap_{i \in I} f^{-1}(B_i)$

^5

6. Gegeben sei eine injektive Funktion $f : X \to Y$.
	Beweisen Sie die folgenden Aussagen:
	1. $\forall A \subseteq X : f^{-1}(f(A)) = A$
	2. $\forall (A_i)_{i \in I} \subseteq \mathcal{P}(X) : f(\bigcap_{i \in I} A_i) = \bigcap_{i \in I} f(A_i)$

^6

7. Gegeben sei eine surjektive Funktion $f : X \to Y$.
	Beweisen Sie die folgende Aussage:
	
	$$
		\forall B \subseteq Y : f(f^{-1}(B)) = B
	$$

^7

8. Beweisen Sie:
	1. Die Gleichmächtigkeit von Mengen ist eine Äquivalenzrelation.
	2. Teilmengen abzählbarer Mengen sind abzählbar.
	3. Endliche kartesische Produkte abzählbarer Mengen sind abzählbar.
	4. Abzählbare Vereinigungen abzählbarer Mengen sind abzählbar.

^8

9. Sei $X$ eine endliche Menge bez. $|X|$ die Anzahl der Elemente von $X$.
	Zeigen Sie:
	1. $|X| = n \implies |\mathcal{P}(X)| = 2^n$
	2. $|X| = n \land |Y| = m \implies |\{ f \mid f : X \to Y \text{ ist eine Funktion } \}| = m^n$

^9