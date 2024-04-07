---
type: solution
---

![[psets/muit/assignment 03#^1|assignment 03#^1]]

Da $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $X$ ist, gilt
- $X \in \mathcal{A}$
- $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
- $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A} : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$

$\mathcal{B}_f$ ist eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $Y$, falls
1. $Y \in \mathcal{B}_f$
2. $B \in \mathcal{B}_f \implies B^\complement \in \mathcal{B}_f$
3. $\forall (B_n)_{n \in \mathbb{N}} \in \mathcal{B}_f: \bigcup_{n \in \mathbb{N}} B_n \in \mathcal{B}_f$

Alle Voraussetzungen sind erfüllt, da
1. $X \in \mathcal{A} \land f^{-1}(Y) = X \implies Y \in \mathcal{B}_f$
2. $B \in B_f \implies f^{-1}(B) \in \mathcal{A} \implies (f^{-1}(B))^\complement = f^{-1}(B^\complement) \in \mathcal{A} \implies B^\complement \in \mathcal{B}_f$
3. $\forall (B_n)_{n \in \mathbb{N}} \in \mathcal{B}_f \implies (f^{-1}(B_n))_{n \in \mathbb{N}} \in \mathcal{A} \implies \bigcup_{n \in \mathbb{N}} f^{-1}(B_n) = f^{-1}(\bigcup_{n \in \mathbb{N}} B_n) \in \mathcal{A} \implies \bigcup_{n \in \mathbb{N}} B_n \in \mathcal{B}$

---

![[psets/muit/assignment 03#^2|assignment 03#^2]]

Da $f$ $(\mathcal{A}, \mathcal{B})$-[[zettel/Funktion A-S-messbar|messbar]] ist, gilt
- $\forall B \in \mathcal{B} : f^{-1}(B) \in \mathcal{A}$

Sei $\mathcal{E} \subseteq \mathcal{P}(Y)$ mit
- $\{ B \in \mathcal{E} \mid f^{-1}(B) \in A \} = \mathcal{B}$

Alle Voraussetzungen sind erfüllt, da
1. $\mathcal{E} \subseteq \mathcal{P}(Y) \implies \mathcal{B} = \{ B \in \mathcal{E} \mid f^{-1}(B) \in \mathcal{A} \} \subseteq \{ B \in \mathcal{P}(Y) \mid f^{-1}(B) \in \mathcal{A} \} = \mathcal{B}_f$
2. $\mathcal{B} \subseteq \mathcal{B}_f \land \forall B \in \mathcal{B}_f : f^{-1}(B) \in \mathcal{A} \implies f^{-1}(\mathcal{B}) \subseteq f^{-1}(\mathcal{B}_f) \subseteq \mathcal{A}$

---

![[psets/muit/assignment 03#^3|assignment 03#^3]]

$f$ ist $(\mathcal{A}, \mathcal{B})$-[[zettel/Funktion A-S-messbar|messbar]], falls
- $f \in \{ f_B \mid B \in \mathcal{B} \land \forall x \in X : f_B(x) := B \}\}$

---

![[psets/muit/assignment 03#^4|assignment 03#^4]]

$$
	\begin{aligned}
		\underbrace{\forall r \in \mathbb{R} : \{ x \in X \mid I_A(x) \le r \} \in \mathcal{A}}_{I_A \text{ ist } A\text{-messbar}} & \iff && \underbrace{\forall r \in (-\infty, 0) : \overbrace{\{ x \in X \mid I_A(x) \le r \}}^\emptyset \in \mathcal{A}}_\text{nach Definition} \\
		& \quad\ \land && \forall r \in [0, 1) : \overbrace{\{ x \in X \mid I_A(x) \le r \}}^{A^\complement} \in \mathcal{A} \\
		& \quad\ \land && \underbrace{\forall r \in [1, +\infty) : \overbrace{\{ x \in X \mid I_A(x) \le r \}}^X \in \mathcal{A}}_\text{nach Definition} \\
		& \iff && A^\complement \in \mathcal{A} \iff A \in \mathcal{A}
	\end{aligned}
$$

---

![[psets/muit/assignment 03#^5|assignment 03#^5]]

$f$ ist $\mathcal{B}^*$-[[zettel/Funktion A-messbar|messbar]], falls
1. $\forall r \in \mathbb{R} : \{ x \in \mathbb{R} \mid f(x) \le r \} \in \mathcal{B}^*$

%%
Sei $(s_n)_{n \in \mathbb{N}}$ die Menge der Sprungstellen von $f$ mit
- $(s_n)_{n \in \mathbb{N}}$ [offensichtlich](https://de.wikipedia.org/wiki/Monotone_reelle_Funktion#Eigenschaften) abzählbar
- $\forall r \in \mathbb{R} : (s_n^{(r)})_{n \in \overline{\mathbb{N}}_0} := \begin{cases} -\infty, & n = 0 \\ (\max(s_n, r))_{n \in \mathbb{N}}, & n \in \mathbb{N} \\ +\infty, & n = \infty \end{cases}$

Alle Voraussetzungen sind erfüllt, da
1. $\forall r \in \mathbb{R} : \{ x \in \mathbb{R} \mid f(x) \le r \} = \bigcup_{n \in \overline{\mathbb{N}}_0} \{ x \in \mathbb{R} \mid s_n^{(r)} \lt f(x) \le s_{n + 1}^{(r)} \} = \bigcup_{n \in \overline{\mathbb{N}}_0} \underbrace{(\min(\{ x \in X \mid f(x) = s_n^{(r)} \}), \max(\{ x \in X \mid f(x) = s_{n+1}^{(r)} \})]}_{\in \mathcal{B}^*} \in \mathcal{B}^*$
%%

Alle Voraussetzungen sind erfüllt, da
1. $\forall r \in \mathbb{R} : \{ x \in \mathbb{R} \mid f(x) \le r \} = \underbrace{(-\infty, \overbrace{\max(\{ x \in X \mid f(x) = r \})}^{\in \mathbb{R}}]}_{\in \mathcal{I}^1} \in \sigma(\mathcal{I}^1) = \mathcal{B}^*$

---

![[psets/muit/assignment 03#^6|assignment 03#^6]]

$\sin^+ = \max(+\sin, 0) = \begin{cases} +\sin(x), & \exists k \in \mathbb{N}_0 : x \in (2k\pi, (2k+1)\pi) \\ 0, & \text{sonst} \end{cases}$
$\sin^- = \max(-\sin, 0) = \begin{cases} -\sin(x), & \exists k \in \mathbb{N}_0 : x \notin (2k\pi, (2k+1)\pi) \\ 0, & \text{sonst} \end{cases}$

---

![[psets/muit/assignment 03#^7|assignment 03#^7]]

1. Da $\mathcal{A}$ eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $X$ ist, gilt
	- $X \in \mathcal{A}$
	- $A \in \mathcal{A} \implies A^\complement \in \mathcal{A}$
	- $\forall (A_n)_{n \in \mathbb{N}} \in \mathcal{A} : \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A}$
	
	$\mathcal{A}_C$ ist eine $\sigma$-[[zettel/σ-Algebra|Algebra]] auf $C$, falls
	1. $C \in \mathcal{A}_C$
	2. $A_C \in \mathcal{A}_C \implies A_C \in \mathcal{A}_C$
	3. $\forall (A_{C_n})_{n \in \mathbb{N}} \in \mathcal{A}_C : \bigcup_{n \in \mathbb{N}} A_{C_n} \in \mathcal{A}_C$
	
	Alle Voraussetzungen sind erfüllt, da
	1. $X \in \mathcal{A} \implies X \cap C = C \in \mathcal{A}_C$
	2. $A_C \in \mathcal{A}_C \implies \exists A \in \mathcal{A} : A_C \subseteq A \land (A \setminus A_C)_C = \emptyset \implies A^\complement \in \mathcal{A} \implies A^\complement \cap C = A_C^\complement \in \mathcal{A}_C$
	3. $\forall (A_{C_n})_{n \in \mathbb{N}} \in \mathcal{A}_C : \exists (A_n)_{n \in \mathbb{N}} \in \mathcal{A} : (A_n \cap C)_{n \in \mathbb{N}} = (A_{C_n})_{n \in \mathbb{N}} \implies \bigcup_{n \in \mathbb{N}} A_n \in \mathcal{A} \implies \bigcup_{n \in \mathbb{N}} A_n \cap C = \bigcup_{n \in \mathbb{N}} A_{C_n} \in \mathcal{A}_C$
2. Da $f$ $(\mathcal{A}, \mathcal{B})$-[[zettel/Funktion A-S-messbar|messbar]] ist, gilt
	- $\forall B \in \mathcal{B} : f^{-1}(B) \in \mathcal{A}$
	
	$f|_C$ ist $(\mathcal{A}_C, \mathcal{B})$-[[zettel/Funktion A-S-messbar|messbar]]
	1. $\forall B \in \mathcal{B} : f|_C^{-1}(B) \in \mathcal{A}_C$
	
	Alle Voraussetzungen sind erfüllt, da
	1. $\forall B \in \mathcal{B} : f^{-1}(B) = \{ x \in X \mid f(x) \in B \} \in \mathcal{A} \implies \{ x \in X \mid f(x) \in B \} \cap C = \{ x \in C \mid f(x) \in B \} = f|_C^{-1}(B) \in \mathcal{A}_C$

---

![[psets/muit/assignment 03#^8|assignment 03#^8]]

$\frac{f}{g}$ ist [[zettel/Funktion A-messbar|messbar]], falls
1. $\forall r, \alpha \in \mathbb{R} : \{ \alpha \cdot f \le r \} \in \mathcal{A} \land \{ f \le \alpha \cdot g \} \in \mathcal{A} \implies \left\{ \frac{f}{g} \le r \right\} = \{ f \le r \cdot g \} \in \mathcal{A}$

---

![[psets/muit/assignment 03#^9|assignment 03#^9]]

---

![[psets/muit/assignment 03#^10|assignment 03#^10]]

$$
	f \in E(X, \mathcal{A}) \implies \exists (a_i)_{i \in \mathbb{N}} \in \mathbb{R}, (A_i)_{i \in \mathbb{N}} \in \mathcal{A} : f = \sum_{i=1}^n a_i \cdot I_{A_i} \implies \alpha \cdot f = \alpha \sum_{i=1}^n a_i \cdot I_{A_i} = \sum_{i=1}^n \underbrace{(\alpha \cdot a_i)}_{\beta_i} \cdot I_{A_i} = \sum_{i=1}^n \beta_i \cdot I_{A_i} \implies \alpha \cdot f \in E(X, \mathcal{A})
$$

$$
	\int \alpha \cdot f d\mu = \sum_{i=1}^n \alpha \cdot a_i \cdot \mu(A_i) = \alpha \sum_{i=1}^n a_i \cdot \mu(A_i) = \alpha \int f d\mu
$$

---

![[psets/muit/assignment 03#^11|assignment 03#^11]]

1. 

$$
	f \in \overline{Z(X, \mathcal{A})} \implies \exists (f_n)_{n \in \mathbb{N}} \in E(X, \mathcal{A}) : \int \alpha \cdot f d\mu = \sup_{n \in \mathbb{N}} \int \alpha f_n d\mu = \sup_{n \in \mathbb{N}} \sum_{i=1}^n \alpha \cdot a_i^{(n)} \cdot I_{A_i^{(n)}} = \alpha \cdot \sup_{n \in \mathbb{N}} \sum_{i=1}^n a_i^{(n)} \cdot I_{A_i^{(n)}} = \alpha \cdot \sup_{n \in \mathbb{N}} \int f_n d\mu = \alpha \cdot \int f d\mu
$$

2. 

$$
	\int (f + g) d\mu = \exists (f_n + g_n)_{n \in \mathbb{N}} \in E(X, \mathcal{A}) : \int f + g d\mu = \sup_{n \in \mathbb{N}} \int f_n + g_n d\mu = \sup_{n \in \mathbb{N}} \sum_{i=1}^n a^{(f_n + g_n)} \cdot I_{A_i^{(f_n + g_n)}} = \sup_{n \in \mathbb{N}} \sum_{i=1}^n a^{(f_n)} \cdot I_{A_i^{(f_n)}} + \sup_{n \in \mathbb{N}} \sum_{i=1}^n a^{(g_n)} \cdot I_{A_i^{(g_n)}} = \sup_{n \in \mathbb{N}} \int f_n d\mu + \sup_{n \in \mathbb{N}} \int g_n d\mu = \int f d\mu + \int g d\mu
$$

---

![[psets/muit/assignment 03#^12|assignment 03#^12]]

Es gilt
- $f^+ = \sum_{n \in 2\mathbb{N}} n \cdot (n + 1) \cdot I_{(\frac{1}{n+1}, \frac{1}{n}]}$
- $f^- = \sum_{n \in 2\mathbb{N}-1} n \cdot (n + 1) \cdot I_{(\frac{1}{n+1}, \frac{1}{n}]}$
- $\int f^+ d\lambda = \sum_{n \in 2\mathbb{N}} n \cdot (n + 1) \cdot \lambda \left(\left( \frac{1}{n+1}, \frac{1}{n} \right]\right) = \sum_{n \in 2\mathbb{N}} n \cdot (n + 1) \cdot \left( \frac{1}{n} - \frac{1}{n+1} \right) = \sum_{n \in 2\mathbb{N}} n + 1 - n = \sum_{n \in 2\mathbb{N}} 1 = \infty$
- $\int f^- d\lambda = \sum_{n \in 2\mathbb{N}-1} n \cdot (n + 1) \cdot \lambda \left(\left( \frac{1}{n+1}, \frac{1}{n} \right]\right) = \sum_{n \in 2\mathbb{N}-1} n \cdot (n + 1) \cdot \left( \frac{1}{n} - \frac{1}{n+1} \right) = \sum_{n \in 2\mathbb{N}-1} n + 1 - n = \sum_{n \in 2\mathbb{N}-1} 1 = \infty$

$f$ ist weder integrierbar noch quasiintegrierbar, falls
- $\int f d\lambda$ nicht definiert ist

Alle Voraussetzungen sind erfüllt, da
- $\int f d\lambda = \int f^+ d\lambda + \int f^- d\lambda = \infty - \infty = \text{n. d.}$

---

![[psets/muit/assignment 03#^13|assignment 03#^13]]

---

![[psets/muit/assignment 03#^14|assignment 03#^14]]

---

![[psets/muit/assignment 03#^15|assignment 03#^15]]

---

![[psets/muit/assignment 03#^16|assignment 03#^16]]

---

![[psets/muit/assignment 03#^17|assignment 03#^17]]

---

![[psets/muit/assignment 03#^18|assignment 03#^18]]

---

![[psets/muit/assignment 03#^19|assignment 03#^19]]

---

![[psets/muit/assignment 03#^20|assignment 03#^20]]

---

![[psets/muit/assignment 03#^21|assignment 03#^21]]