![[psets/muit/assignment 02#^1]]

Sei $A = \left( \pmatrix{a_1 \\ a_2}, \pmatrix{b_1 \\ b_2} \right], B = \left( \pmatrix{c_1 \\ c_2}, \pmatrix{d_1 \\ d_2} \right] \in \mathcal{I}^2$

1. 

$$
	\emptyset = \left( \pmatrix{0 \\ 0}, \pmatrix{0 \\ 0} \right] \in \mathcal{I}^2
$$

2. 

$$
	 A \cap B = \left( \underbrace{\pmatrix{\max(a_1, c_1) \\ \max(a_2, c_2)}}_{\in \mathbb{R^2}}, \underbrace{\pmatrix{\min(b_1, d_1) \\ \min(b_2, d_2)}}_{\in \mathbb{R^2}} \right] \in \mathcal{I}^2
$$

3. 

$$
	A \setminus B = A \cap B^\complement = \left( \pmatrix{a_1 \\ a_2}, \pmatrix{b_1 \\ b_2} \right] \cap \left(\left( \pmatrix{-\infty \\ -\infty}, \pmatrix{c_1 \\ c_2} \right] \cup \left( \pmatrix{d_1 \\ d_2}, \pmatrix{+\infty \\ +\infty} \right]\right) = \left(\left( \pmatrix{a_1 \\ a_2}, \pmatrix{b_1 \\ b_2} \right] \cap \left( \pmatrix{-\infty \\ -\infty}, \pmatrix{c_1 \\ c_2} \right]\right) \cup \left(\left( \pmatrix{a_1 \\ a_2}, \pmatrix{b_1 \\ b_2} \right] \cap \left( \pmatrix{d_1 \\ d_2}, \pmatrix{+\infty \\ +\infty} \right]\right) = \overbrace{\underbrace{\left( \pmatrix{a_1 \\ a_2}, \underbrace{\pmatrix{\min(b_1, c_1) \\ \min(b_2, c_2)}}_{\in \mathbb{R}^2} \right]}_{\in \mathcal{I}^2} \cup \underbrace{\left( \underbrace{\pmatrix{\max(a_1, d_1) \\ \max(a_2, d_2)}}_{\in \mathbb{R}^2}, \pmatrix{b_1 \\ b_2} \right]}_{\in \mathcal{I}^2}}^\text{p. d.} \in \mathcal{I}^+
$$

---

![[psets/muit/assignment 02#^2]]

Da $\mathcal{A}$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $X$ ist, gilt
- $X \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
- $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A} : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

$$
	\forall n \in \mathbb{N} : A_n \in \mathcal{A} \implies \forall n \in \mathbb{N} : A_n^\complement \in \mathcal{A} \implies \bigcup_{n \in \mathbb{N}} A_n^\complement = \left( \bigcap_{n \in \mathbb{N}} A_n \right)^\complement \in \mathcal{A}
$$

---

![[psets/muit/assignment 02#^3]]

$\mathcal{A}$ ist eine $\sigma$-[[sigma-Algebra|Algebra]] auf $X$, falls
1. $X \in \mathcal{A}$
2. $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
3. $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

Alle Voraussetzungen sind erfüllt, da
1. $X^\complement = \emptyset$ abzählbar $\implies$ $X \in \mathcal{A}$
2. $A \in \mathcal{A} \implies A$ abzählbar $\lor A^\complement$ abzählbar $\implies A^\complement \in \mathcal{A}$ mit ${A^\complement}^\complement = A$
3. 
	1. $\forall n \in \mathbb{N} : A_n$ abzählbar $\implies$ $\bigcup_{n \in \mathbb{N}} A_n$ abzählbar
	2. $\exists k \in \mathbb{N} : A_k$  überabzählbar $\implies$ $A_k^\complement$ abzählbar $\implies$ $( \bigcup_{n \in \mathbb{N}} A_n)^\complement = \bigcap_{n \in \mathbb{N}} A_n^\complement$ abzählbar

---

![[psets/muit/assignment 02#^4]]

Da $\mathcal{D}$ ein [[Dynkin-System]] auf $X$ ist, gilt
- $X \in \mathcal{D}$
- $A \in \mathcal{D} \implies A^\complement \in \mathcal{D}$
- $\forall (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{D} : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{D}$

$$
	B \in \mathcal{D} \implies B^\complement \in \mathcal{D} \implies \underbrace{B^\complement \cup A}_\text{p. d.} \in \mathcal{D} \implies (B^\complement \cup A)^\complement = B \cap A^\complement = B \setminus A \in \mathcal{D}
$$

---

![[psets/muit/assignment 02#^5]]

Da $\mathcal{B}$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $Y$ ist, gilt
- $Y \in \mathcal{B}$
- $B \in \mathcal{B} \implies B^\complement \in \mathcal{B}$
- $\forall (B_n)_{n \in \mathbb{N}} \in \mathcal{B}: \bigcup_{n \in \mathbb{N}} B_n \in \mathcal{B}$

$\mathcal{A}$ ist eine $\sigma$-[[sigma-Algebra|Algebra]] auf $X$, falls
1. $X \in \mathcal{A}$
2. $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
3. $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$


Alle Voraussetzungen sind erfüllt, da
1. $Y \in \mathcal{B} \implies f^{-1}(Y) = X \in \mathcal{A}$
2. $A \in \mathcal{A} \implies f(A) \in \mathcal{B} \implies Y \setminus f(A) \in \mathcal{B} \implies f^{-1}(Y \setminus f(A)) = \{ x \in X = f^{-1}(Y) \mid x \notin f^{-1}(f(A)) = A \} = A^\complement \in \mathcal{A}$
3. $(A_n)_{n \in \mathbb{N}} \in \mathcal{A} \implies (f(A_n))_{n \in \mathbb{N}} \in \mathcal{B} \implies \bigcup_{n \in \mathbb{N}} f(A_n) = \{ f(a) \mid \exists n \in \mathbb{N} : a \in A_n \} \in \mathcal{B} \implies f^{-1}(\{ f(a) \mid \exists n \in \mathbb{N} : a \in A_n \}) = \{ f^{-1}(f(a)) \mid \exists n \in \mathbb{N} : a \in A_n \} = \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

---

![[psets/muit/assignment 02#^6]]

1. Falls $\forall i \in I : \mathcal{A}_i$ eine $\sigma$-[[sigma-Algebra|Algebra]] auf $X$ ist, gilt
	- $\forall i \in I : X \in \mathcal{A}_i$
	- $\forall i \in I : A \in \mathcal{A}_i \implies A^\complement \in \mathcal{A}_i$
	- $\forall i \in I, (A_n)_{n \in \mathbb{N}} \in \mathcal{A_i}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A_i}$
	
	$\mathcal{A}$ ist eine $\sigma$-[[sigma-Algebra|Algebra]] auf $X$, falls
	1. $X \in \mathcal{A}$
	2. $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
	3. $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A}: \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$
	
	Alle Voraussetzungen sind erfüllt, da
	1. $\forall i \in I : X \in \mathcal{A}_i \implies X \in \bigcap_{i \in I} \mathcal{A}_i = \mathcal{A}$
	2. $A \in \mathcal{A} \implies \forall i \in I : A \in \mathcal{A}_i \implies \forall i \in I : A^\complement \in \mathcal{A}_i \implies A^\complement \in \bigcap_{i \in I} \mathcal{A}_i = \mathcal{A}$
	3. $(A_n)_{n \in \mathbb{N}} \in \mathcal{A} \implies \forall i \in I : (A_n)_{n \in \mathbb{N}} \in \mathcal{A}_i \implies \forall i \in I : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}_i \implies \bigcup_{n \in \mathbb{N}} A_n \in \bigcap_{i \in I} \mathcal{A}_i = \mathcal{A}$
2. Falls $\forall i \in I : \mathcal{A}_i$ ein [[Dynkin-System]] auf $X$ ist, gilt
	- $\forall i \in I : X \in \mathcal{A}_i$
	- $\forall i \in I : A \in \mathcal{A}_i \implies A^\complement \in \mathcal{A}_i$
	- $\forall i \in I, (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{A}_i : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}_i$
	
	$\mathcal{A}$ ist eine [[Dynkin-System]] auf $X$, falls
	1. $X \in \mathcal{A}$
	2. $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
	3. $\forall (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$
	
	Alle Voraussetzungen sind erfüllt, da
	1. $\forall i \in I : X \in \mathcal{A}_i \implies X \in \bigcap_{i \in I} \mathcal{A}_i = \mathcal{A}$
	2. $A \in \mathcal{A} \implies \forall i \in I : A \in \mathcal{A}_i \implies \forall i \in I : A^\complement \in \mathcal{A}_i \implies A^\complement \in \bigcap_{i \in I} \mathcal{A}_i = \mathcal{A}$
	3. $(A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \forall i \in I : (A_n)_{n \in \mathbb{N}} \in \mathcal{A}_i \overset{(A_n)_{n \in \mathbb{N}} \text{ p. d.}}{\implies} \forall i \in I : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}_i \implies \bigcup_{n \in \mathbb{N}} A_n \in \bigcap_{i \in I} \mathcal{A}_i = \mathcal{A}$

---

![[psets/muit/assignment 02#^7]]

Da $\delta(\mathcal{E})$ ein [[Durchschnittsstabilität|durchschnittsstabiles]] [[Dynkin-System]] bzw. eine $\sigma$-[[sigma-Algebra|Algebra]] auf $X$ ist, gilt
- $X \in \delta(\mathcal{E})$
- $A \in \delta(\mathcal{E}) \implies A^\complement \in \delta(\mathcal{E})$
- $\forall (A_n)_{n \in \mathbb{N}} \in \delta(\mathcal{E}) : \bigcup_{n \in \mathbb{N}} A_n \in \delta(\mathcal{E})$

$\mathcal{D}_D$ ist eine [[Dynkin-System]] auf $X$, falls
1. $X \in \mathcal{D}_D$
2. $A \in \mathcal{D}_D \implies A^\complement \in \mathcal{D}_D$
3. $\forall (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{D}_D : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{D}_D$

Alle Voraussetzungen sind erfüllt, da
1. $\forall D \in \delta(\mathcal{E}) : X \cap D = D \in \delta(\mathcal{E}) \implies X \in \mathcal{D}_D$
2. $\forall D \in \delta(\mathcal{E}), A \in \mathcal{D}_D : A \cap D \in \delta(\mathcal{E}) \implies (A \cap D)^\complement = A^\complement \cup D^\complement \in \delta(\mathcal{E}) \underset{\delta(\mathcal{E}) \ \cap\text{-stabil}}{\overset{D \in \delta(\mathcal{E})}{\implies}} (A^\complement \cup D^\complement) \cap D = (A^\complement \cap D) \cup \underbrace{(D^\complement \cap D)}_\emptyset \in \delta(\mathcal{E}) \implies A^\complement \in \mathcal{D}_D$
4. $\forall D \in \delta(\mathcal{E}), (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{D}_D \implies (A_n \cap D)_{n \in \mathbb{N}} \in \delta(\mathcal{E}) \implies \bigcup_{n \in \mathbb{N}} (A_n \cap D) = \bigcup_{n \in \mathbb{N}} A_n \cap D \in \delta(\mathcal{E}) \implies \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{D}_D$

---

![[psets/muit/assignment 02#^8]]

---

![[psets/muit/assignment 02#^9]]

$$
	B = \underbrace{(B \setminus A) \cup A}_\text{p. d.} \overset{\mu \ \sigma\text{-additiv}}{\implies} \mu(B) = \mu(B \setminus A) + \mu(A) \implies \mu(B \setminus A) = \mu(B) - \mu(A)
$$

$$
	(A \subseteq B \implies \mu(A) \le \mu(B)) \land \mu(A) = \infty \implies \infty \le \mu(B) \implies \mu(B) = \infty \implies \mu(B \setminus A) = \mu(B) - \mu(A) = \infty - \infty = \text{n. d.}
$$

---

![[psets/muit/assignment 02#^10]]

$\mathcal{D}_n$ ist ein [[Dynkin-System]], falls
1. $X \in \mathcal{D}_n$
2. $A \in \mathcal{D}_n \implies A^\complement \in \mathcal{D}_n$
3. $\forall (A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{D}_n : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{D}_n$

Alle Voraussetzungen sind erfüllt, da
1. $\forall n \in \mathbb{N} : X \cap E_n = E_n \implies \forall i \in \{ 1, 2 \} : \mu_i(X \cap E_n) = \mu_i(E_n) \implies \mu_1(X \cap E_n) = \mu_2(X \cap E_n) \implies X \in \mathcal{D}_n$
2. $\forall n \in \mathbb{N}, A \in \mathcal{D}_n : \mu_1(A \cap E_n) = \mu_2(A \cap E_n) \land (E_n = \underbrace{(A \cap E_n) \cup (A^\complement \cap E_n)}_\text{p. d.} \overset{\mu \ \sigma\text{-additiv}}{\implies} \forall i \in \{ 1, 2 \} : \mu_i(E_n) = \mu_i(A \cap E_n) + \mu_i(A^\complement \cap E_n) \implies \forall i \in \{ 1, 2 \} : \mu(A^\complement \cap E_n) = \mu(E_n) - \mu(A \cap E_n)) \implies \mu_1(A^\complement \cap E_n) = \mu_2(A^\complement \cap E_n) \implies A^\complement \in \mathcal{D}_n$
3. $\forall n \in \mathbb{N}, (A_k)_{k \in \mathbb{N}} \text{ p. d.} \in \mathcal{D}_n : (\mu_1(A_k \cap E_n))_{k \in \mathbb{N}} = (\mu_2(A_k \cap E_n))_{k \in \mathbb{N}} \land \forall i \in \{ 1, 2 \} : \sum_{k \in \mathbb{N}} \mu_i(A_k \cap E_n) \overset{\mu \ \sigma\text{-additiv}}{=} \mu_i(\underbrace{\bigcup_{k \in \mathbb{N}} A_k}_\text{p. d.} \cap E_n) \implies \mu_1(\bigcup_{k \in \mathbb{N}} A_k \cap E_n) = \mu_2(\bigcup_{k \in \mathbb{N}} A_k \cap E_n) \implies \bigcup_{k \in \mathbb{N}} A_k \in \mathcal{D}_n$

---

![[psets/muit/assignment 02#^11]]

1. 

$$
	\begin{aligned}
		& A \cup B & = & \underbrace{(A \cap B) \cup (A \setminus B) \cup (B \setminus A)}_\text{p. d.} \\
		\overset{\mu \ \sigma\text{-additiv}}{\implies} & \mu(A \cup B) & = & \mu(A \cap B) + \mu(A \setminus B) + \mu(B \setminus A) \\
		&& = & \overbrace{\mu(A \cap B) + \mu(A \setminus B)}^{\mu(A)} \\
		&& + & \rlap{\overbrace{\phantom{\mu(B \setminus A) + \mu(A \cap B)}}^{\mu(B)}}\mu(B \setminus A) + \underbrace{\mu(A \cap B) - \mu(A \cap B)}_0 \\
		&& = & \mu(A) + \mu(B) - \mu(A \cap B)
	\end{aligned}
$$

2. 

$$
	\begin{aligned}
		& A \cup B \cup C & = & \underbrace{(A \cap B \cap C) \cup ((A \cap B) \setminus C) \cup ((A \cap C) \setminus B) \cup ((B \cap C) \setminus A) \cup (A \setminus (B \cap C)) \cup (B \setminus (A \cap C)) \cup (C \setminus (A \cap B))}_\text{p. d.} \\
		\overset{\mu \ \sigma\text{-additiv}}{\implies} & \mu(A \cup B \cup C) & = & \mu(A \cap B \cap C) + \mu((A \cap B) \setminus C) + \mu((A \cap C) \setminus B) + \mu((B \cap C) \setminus A) + \mu(A \setminus (B \cap C)) + \mu(B \setminus (A \cap C)) + \mu(C \setminus (A \cap B)) \\
		&& = & \overbrace{\mu(A \cap B \cap C) + \mu((A \cap B) \setminus C) + \mu((A \cap C) \setminus B) + \mu(A \setminus (B \cap C))}^{\mu(A)} \\
		&& + & \rlap{\overbrace{\phantom{\mu(B \setminus (A \cap C)) + \mu((B \cap C) \setminus A) + \mu(A \cap B \cap C) + \mu((A \cap B) \setminus C)}}^{\mu(B)}} \mu(B \setminus (A \cap C)) + \mu((B \cap C) \setminus A) + \underbrace{\mu(A \cap B \cap C) + \mu((A \cap B) \setminus C) - \overbrace{\mu(A \cap B \cap C) - \mu((A \cap B) \setminus C)}^{\mu(A \cap B)}}_0 \\
		&& + & \rlap{\overbrace{\phantom{\mu(C \setminus (A \cap B)) + \mu(A \cap B \cap C) + \mu((A \cap C) \setminus B) + \mu((B \cap C) \setminus A)}}^{\mu(C)}} \mu(C \setminus (A \cap B)) + \underbrace{\mu(A \cap B \cap C) + \mu((A \cap C) \setminus B) + \mu((B \cap C) \setminus A) - \overbrace{\mu(A \cap B \cap C) - \mu((A \cap C) \setminus B)}^{\mu(A \cap C)} - \mu((B \cap C) \setminus A)}_0 \\
		&& = & \mu(A) + \mu(B) + \mu(C) - \mu(A \cap B) - \mu(A \cap C) - \rlap{\overbrace{\phantom{\mu((B \cap C) \setminus A) - \mu(A \cap B \cap C)}}^{\mu(B \cap C)}} \mu((B \cap C) \setminus A) - \underbrace{\mu(A \cap B \cap C) + \mu(A \cap B \cap C)}_0 \\
		&& = & \mu(A) + \mu(B) + \mu(C) - \mu(A \cap B) - \mu(A \cap C) - \mu(B \cap C) + \mu(A \cap B \cap C)
	\end{aligned}
$$

---

![[psets/muit/assignment 02#^12]]

Es gilt
- $A \bigtriangleup \emptyset = (A \setminus \emptyset) \cup (\emptyset \setminus A) = A \cup \emptyset = A$
- $(A \bigtriangleup C) \bigtriangleup (C \bigtriangleup D) = A \bigtriangleup (C \bigtriangleup C) \bigtriangleup B = A \bigtriangleup \emptyset \bigtriangleup B = A \bigtriangleup B$

Alle Voraussetzungen sind erfüllt, da
1. $\forall A \in \mathcal{A} : A \bigtriangleup A = \underbrace{(A \setminus A)}_\emptyset \cup \underbrace{(A \setminus A)}_\emptyset = \emptyset \implies d(A, A) = \mu(A \bigtriangleup A) = \mu(\emptyset) = 0$
2. $\forall A, B \in \mathcal{A} : A \bigtriangleup B = (A \setminus B) \cup (B \setminus A) = (B \setminus A) \cup (A \setminus B) = B \bigtriangleup A \implies d(A, B) = A \bigtriangleup B = B \bigtriangleup A = d(B, A)$
3. $\forall A, B, C \in \mathcal{A} : A \bigtriangleup B = (A \bigtriangleup C) \bigtriangleup (C \bigtriangleup B) \subseteq (A \bigtriangleup C) \cup (C \bigtriangleup B) \implies \mu(A \bigtriangleup C) \le \mu((A \bigtriangleup C) \cup (C \bigtriangleup B)) \le \mu(A \bigtriangleup C) + \mu(C \bigtriangleup B) \implies d(A, B) \le d(A, C) + d(C, B)$

---

![[psets/muit/assignment 02#^13]]

---

![[psets/muit/assignment 02#^14]]

Da $\mu$ ein [[Maß]] auf $\mathcal{A}$ ist, gilt
- $\mu(\emptyset) = 0$
- $(A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \mu( \bigcup_{n \in \mathbb{N}} A_n) = \sum_{n \in \mathbb{N}} \mu(A_n)$

$(X, \mathcal{A}, \nu)$ ist ein [[Maßraum]], falls
1. $\nu$ ist ein [[Maß]] auf $\mathcal{A}$ ist

$\nu$ ist ein [[Maß]] auf $\mathcal{A}$, falls
1. $\nu(\emptyset) = 0$
2. $(A_n)_{n \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \nu( \bigcup_{n \in \mathbb{N}} A_n) = \sum_{n \in \mathbb{N}} \nu(A_n)$

Alle Voraussetzungen sind erfüllt, da
1. 
	1. $\nu(\emptyset) = \mu(\emptyset \cap B) = \mu(\emptyset) = 0$
	2. $\nu(\bigcup_{n \in \mathbb{N}} A_n) = \mu(\bigcup_{n \in \mathbb{N}} A_n \cap B) = \mu\underbrace{(\bigcup_{n \in \mathbb{N}} (A_n \cap B))}_\text{p. d.} = \sum_{n \in \mathbb{N}} \mu(A_n \cap B) = \sum_{n \in \mathbb{N}} \nu(A_n)$

---

![[psets/muit/assignment 02#^15]]

Da $\mu$ ein [[Maß]] auf $\mathcal{A}$ ist, gilt
- $\mu(\emptyset) = 0$
- $(A_k)_{k \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \mu( \bigcup_{k \in \mathbb{N}} A_k) = \sum_{k \in \mathbb{N}} \mu(A_k)$

$(X, \mathcal{A}, \nu)$ ist ein [[Maßraum]], falls
1. $\nu$ ist ein [[Maß]] auf $\mathcal{A}$ ist

$\nu$ ist ein [[Maß]] auf $\mathcal{A}$, falls
1. $\nu(\emptyset) = 0$
2. $(A_k)_{k \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \nu( \bigcup_{k \in \mathbb{N}} A_k) = \sum_{k \in \mathbb{N}} \nu(A_k)$

Alle Voraussetzungen sind erfüllt, da
1. 
	1. $\nu(\emptyset) = \sum_{i=1}^n a_i\mu_i(\emptyset) = \sum_{i=1}^n a_i \cdot 0 = 0$
	2. $\nu(\bigcup_{k \in \mathbb{N}} A_k) = \sum_{i=1}^n a_i \mu(\bigcup_{k \in \mathbb{N}} A_k) = \sum_{i=1}^n a_i \sum_{k \in \mathbb{N}} \mu(A_k) = \sum_{k \in \mathbb{N}}\sum_{i=1}^n a_i\mu(A_k) = \sum_{k \in \mathbb{N}} \nu(A_k)$

---

![[psets/muit/assignment 02#^16]]

$\nu$ ist ein [[Maß|Wahrscheinlichkeitsmaß]] auf $\mathcal{A}$, falls
1. $\nu(\emptyset) = 0$
2. $(A_k)_{k \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \nu( \bigcup_{k \in \mathbb{N}} A_k) = \sum_{k \in \mathbb{N}} \nu(A_k)$
3. $\nu(X) = 1$

Alle Voraussetzungen sind erfüllt, da
1. $\nu(\emptyset) = \sum_{n=1}^\infty 2^{-n}\mu_n(\emptyset) = \sum_{n=1}^\infty 2^{-n} \cdot 0 = 0$
2. $\nu(\bigcup_{k \in \mathbb{N}} A_k) = \sum_{n=1}^\infty 2^{-n} \mu_n(\bigcup_{k \in \mathbb{N}} A_k) = \sum_{n=1}^\infty 2^{-n} \sum_{k \in \mathbb{N}} \mu(A_k) = \sum_{k \in \mathbb{N}}\sum_{n=1}^\infty 2^{-n} \mu(A_k) = \sum_{k \in \mathbb{N}} \nu(A_k)$
3. $\nu(X) = \sum_{n=1}^\infty 2^{-n} \mu_n(X) = \sum_{n=1}^\infty 2^{-n} \cdot 1 = 1$

---

![[psets/muit/assignment 02#^17]]

$\mu$ ist ein [[Maß]] auf $\mathcal{P}(\mathbb{N})$, falls
1. $\mu(\emptyset) = 0$
2. $(A_n)_{k \in \mathbb{N}} \text{ p. d.} \in \mathcal{A} \implies \mu( \bigcup_{k \in \mathbb{N}} A_k) = \sum_{k \in \mathbb{N}} \mu(A_k)$

Alle Voraussetzungen sind erfüllt, da
1. $\mu(\emptyset) = 0$ nach Definition
2. $\mu(\bigcup_{k \in \mathbb{N}} A_k) =\sum_{n \in \bigcup_{k \in \mathbb{N}} A_k} a_n = \sum_{k \in \mathbb{N}}\sum_{n \in A_k} a_n = \sum_{k \in \mathbb{N}} \mu(A_k)$