---
type: solution
---

![[psets/muit/assignment 01#^1]]

1. 

$$
	(A^\complement)^\complement = (\{ a \mid a \in A \}^\complement)^\complement = \{ a \mid \overline{a \in A} \}^\complement = \{ a \mid \overline{\overline{a \in A}} \} = \{ a \mid a \in A \} = A
$$

2. 

$$
	\left( \bigcup_{i \in I} A_i \right)^\complement = \{ a \mid \exists i \in I : a \in A_i \}^\complement = \{ a \mid \forall i \in I : a \notin A_i \} = \bigcap_{i \in I} A_i^\complement
$$

$$
	\left( \bigcap_{i \in I} A_i \right)^\complement = \{ a \mid \forall i \in I : a \in A_i \}^\complement = \{ a \mid \exists i \in I : a \notin A_i \} = \bigcup_{i \in I} A_i^\complement
$$

3. 

$$
	\left( \bigcup_{i \in I} A_i \right) \cap \left( \bigcup_{j \in J} B_j \right) = \{ a \mid \exists i \in I : a \in A_i \} \cap \{ b \mid \exists j \in J : b \in B_j \} = \{ x \mid \exists i \in I, j \in J : x \in A_i \land x \in B_j \} ) = \bigcup_{i \in I}\bigcup_{j \in J} (A_i \cap B_j)
$$

$$
	\left( \bigcap_{i \in I} A_i \right) \cup \left( \bigcap_{j \in J} B_j \right) = \{ a \mid \forall i \in I : a \in A_i \} \cup \{ b \mid \forall j \in J : b \in B_j \} = \{ x \mid \forall i \in I, j \in J : x \in A_i \lor x \in B_j \} ) = \bigcap_{i \in I}\bigcap_{j \in J} (A_i \cup B_j)
$$

---

![[psets/muit/assignment 01#^2]]

$$
	\liminf_{n \to \infty} A_n = \bigcup_{m \in \mathbb{N}}\bigcap_{n \ge m} A_n
$$

$$
	\limsup_{n \to \infty} A_n = \bigcap_{m \in \mathbb{N}}\bigcup_{n \ge m} A_n
$$

---

![[psets/muit/assignment 01#^3]]

$$
	\liminf_{n \to \infty} A_n = \bigcup_{m \in \mathbb{N}}\bigcap_{n \ge m} A_n = \bigcup_{m \in \mathbb{N}} \left\{ a \mid \forall n \ge m : a \in \left[ 0, 1 + \frac{1}{n} \right)\right\} = \bigcup_{m \in \mathbb{N}} \left\{ a \mid a \in \lim_{n \to \infty} \left[ 0, 1 + \frac{1}{n} \right)\right\} = \bigcup_{m \in \mathbb{N}} \{ a \mid a \in [0, 1] \} = \bigcup_{m \in \mathbb{N}} [0, 1] = [0, 1]
$$

$$
	\liminf_{n \to \infty} B_n = \bigcup_{m \in \mathbb{N}}\bigcap_{n \ge m} B_n = \bigcup_{m \in \mathbb{N}} \left\{ b \mid \forall n \ge m : b \in \left[ 0, 1 - \frac{1}{n} \right]\right\} = \bigcup_{m \in \mathbb{N}} \left\{ b \mid b \in \left[ 0, 1 - \frac{1}{m} \right]\right\} = \left\{ b \mid \exists m \in \mathbb{N} : b \in  \left[ 0, 1 - \frac{1}{m} \right]\right\} = \lim_{m \to \infty}\left[ 0, 1 - \frac{1}{m} \right] = [0, 1)
$$

$$
	\limsup_{n \to \infty} A_n = \bigcap_{m \in \mathbb{N}}\bigcup_{n \ge m} A_n = \bigcap_{m \in \mathbb{N}} \left\{ a \mid \exists n \ge m : a \in \left[ 0, 1 + \frac{1}{n} \right)\right\} = \bigcap_{m \in \mathbb{N}} \left\{ a \mid a \in \left[ 0, 1 + \frac{1}{m} \right)\right\} = \left\{ a \mid \forall m \in \mathbb{N} : a \in \left[ 0, 1 + \frac{1}{m} \right)\right\} = \left\{ a \mid a \in \lim_{n \to \infty} \left[ 0, 1 + \frac{1}{m} \right)\right\} = \{ a \mid a \in [0, 1] \} = [0, 1]
$$

$$
	\limsup_{n \to \infty} B_n = \bigcap_{m \in \mathbb{N}}\bigcup_{n \ge m} B_n = \bigcap_{m \in \mathbb{N}} \left\{ b \mid \exists n \ge m : b \in \left[ 0, 1 - \frac{1}{n} \right]\right\} = \bigcap_{m \in \mathbb{N}} \left\{ b \mid b \in \lim_{n \to \infty} \left[ 0, 1 - \frac{1}{m} \right]\right\} = \bigcap_{m \in \mathbb{N}} \{ b \mid b \in [0, 1) \} = \bigcap_{m \in \mathbb{N}} [0, 1) = [0, 1)
$$

---

![[psets/muit/assignment 01#^4]]

1. 

$$
	f^{-1}(Y \setminus B) = \{ x \in X \mid f(x) \in Y \setminus B \} = X \setminus \{ x \in X \mid f(x) \in B \} = X \setminus f^{-1}(B)
$$

2. 

$$
	B_1 \cap B_2 = \emptyset \implies f^{-1}(B_1) \cap f^{-1}(B_2) = \{ x \in X \mid f(x) \in B_1 \} \cap \{ x \in X \mid f(x) \in B_2 \} = \{ x \in X \mid f(x) \in B_1 \land f(x) \in B_2 \} = \{ x \in X \mid x \in \{ B_1 \cap B_2 \}\} = \{ x \in X \mid f(x) \in \emptyset \} = \emptyset
$$

3. 

$$
	A \subseteq f^{-1}(f(A)) = f^{-1}(\{ f(x) \in Y \mid x \in A \}) = A \cup (f^{-1}(f(x) \in Y \mid x \in A) \setminus A) = A \cup \{ x \in X \mid x \notin A \land f(x) \in f(A) \}
$$

4. 

$$
	f(f^{-1}(B)) = f(\{ x \in X \mid f(x) \in B \}) = B \setminus \{ y \in B \mid \forall x \in f^{-1}(B) : f(x) \ne y \} \subseteq B
$$

---

![[psets/muit/assignment 01#^5]]

1. 

$$
	f\left( \bigcup_{i \in I} A_i \right) = f(\{ a \mid \exists i \in I : a \in A_i \}) = \{ f(a) \mid \exists i \in I : a \in A_i \} = \bigcup_{i \in I} f(A_i)
$$

2. 

$$
	f\left( \bigcap_{i \in I} A_i \right) = f(\{ a \mid \forall i \in I : a \in A_i \}) = \{ f(a) \mid \forall i \in I : a \in A_i \} \setminus \{ f(a) \mid \exists i \in I, j \in I : a \in A_i \land a \notin A_j \} \subseteq \{ f(a) \mid \forall i \in I : a \in A_i \} = \bigcap_{i \in I} f(A_i)
$$

3. 

$$
	f^{-1}\left( \bigcup_{i \in I} B_i \right) = f^{-1}(\{ b \mid \exists i \in I : b \in B_i \}) = \{ f^{-1}(b) \mid \exists i \in I : b \in B_i \} = \bigcup_{i \in i} f^{-1}(B_i)
$$

4. 

$$
	f^{-1}\left( \bigcap_{i \in I} B_i \right) = f^{-1}(\{ b \mid \forall i \in I : b \in B_i \}) = \{ f^{-1}(b) \mid \forall i \in I : b \in B_i \} \setminus \underbrace{\{ x \in X \mid f(x) \in \bigcap_{j \in I} B_j \land \forall i \in I : x \notin f^{-1}(B_i) \}}_\emptyset = \bigcap_{i \in i} f^{-1}(B_i)
$$

---

![[psets/muit/assignment 01#^6]]

1. 

$$
	f^{-1}(f(A)) = f^{-1}(\{ f(x) \in Y \mid x \in A \}) = A \cup (f^{-1}(f(x) \in Y \mid x \in A) \setminus A) = A \cup \underbrace{\{ x \in X \mid x \notin A \land f(x) \in f(A) \}}_\emptyset = A
$$

2. 

$$
	f\left( \bigcap_{i \in I} A_I \right) = f(\{ a \mid \forall i \in I : a \in A_i \}) = \{ f(a) \mid \forall i \in I : a \in A_i \} \setminus \underbrace{\{ f(a) \mid \exists i \in I, j \in I : a \in A_i \land a \notin A_j \}}_\emptyset = \bigcap_{i \in I} f(A_i)
$$

---

![[psets/muit/assignment 01#^7]]

$$
	f(f^{-1}(B)) = f(\{ x \in X \mid f(x) \in B \}) = B \setminus \underbrace{\{ y \in B \mid \forall x \in f^{-1}(B) : f(x) \ne y \}}_\emptyset = B
$$

---

![[psets/muit/assignment 01#^8]]

1. $A \sim B \implies \exists \varphi : A \to B$ bijektiv

	$\sim$ ist eine Äquivalenzrelation, da gilt
	- Reflexivität: $A = B \implies A \sim B$ z. B. mit $\varphi(x) = \text{id}(x) = x$
	- Symmetrie: $A \sim B \implies B \sim A$ z. B. mit $\varphi_{B \to A} = \varphi_{A \to B}^{-1}$
	- Transitivität $A \sim B \land B \sim C \implies A \sim C$ z. B. mit $\varphi_{A \to C} = \varphi_{A \to B} \circ \varphi_{B \to C}$
2. Sei $B \subset A$ mit
	- $\varphi_A : A \to \mathbb{N}$ injektiv
	- $\varphi_{B \to A} : B \to A$ injektiv

	$\varphi_{B \to A} \circ \varphi_A : B \to \mathbb{N}$ injektiv $\implies$ $B$ abzählbar
3. Sei $n \in \mathbb{N}$, $(A_i)_{i \in \{ 1, \dots, n \}} \sim \mathbb{N}$, $(\varphi_n)_{n \in \{ 1, \dots, n \}}$ mit
	- $\forall i \in \{ 1, \dots, n \} : \varphi_n : A_n \to \mathbb{N}$
	- $\forall i \in \{ 1, \dots, n \} : \{ \varphi_n(x) \mid x \in A_n \} = \{ 1, \dots, n \}$
	- $\exists \varphi : \prod_{i=1}^n A_n \to \mathbb{N}$ injektiv z. B. $\varphi(x) = \sum_{i=1}^n (\varphi_i(x_i) - 1) \cdot \sum_{k=i+1}^n \tau(A_k) + 1$

	$\varphi(\prod_{i=1}^n A_n) \subseteq \mathbb{N} \implies \prod_{i=1}^n A_n \sim \mathbb{N}$
4. Sei $(A_n)_{n \in \mathbb{N}} \sim \mathbb{N}$, $(\varphi_n)_{n \in \mathbb{N}}$, $I_{A_n}$ die [[Indikatorfunktion]] auf $A_n$, $p_n$ die $n$-te Primzahl mit
	- $\forall n \in \mathbb{N} : \varphi_n : A_n \to \mathbb{N}$
	- $\exists \varphi : \bigcup_{n \in \mathbb{N}} A_n \to \mathbb{N}$ injektiv z. B. $\varphi(x) = \sup_{n \in \mathbb{N}} (p_n^{\varphi_n(x)} \cdot I_{A_n}(x))$

	$\varphi(\bigcup_{n \in \mathbb{N}} A_n) \subseteq \mathbb{N} \implies \bigcup_{n \in \mathbb{N}} A_n \sim \mathbb{N}$

---

![[psets/muit/assignment 01#^9]]

1. 

$$
	|\mathcal{P}(X)| = |\bigcup_{i=0}^n \{ A \subseteq X \mid |A| = n \}| = \sum_{i=0}^n |\{ A \subseteq X \mid |A| = n \}| = \sum_{i=0}^n \binom{n}{i} = 2^n
$$

2. $f : X \to Y \text{ ist eine Funktion }$, falls
	- $\forall x \in X : \exists f(x) = y \in Y$

$$
	 |\{ f \mid f : X \to Y \text{ ist eine Funktion } \}| = \left|\left\{ \underbrace{(y_i)_{i \in I} \in Y}_\text{Wähle aus m Elementen} \mid \underbrace{|I| = n}_\text{n Elemente} \land \underbrace{I \in \prod_{i=1}^n \{ 1, \dots, n \}}_\text{mit Zurücklegen und Beachten der Reihenfolge} \right\}\right| = m^n
$$