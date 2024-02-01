Sei $f \in \mathcal{M}_+$, $(f_n)_{n \in \mathbb{N}} \in P+$ [[Funktion|primitive]] [[Funktion|Funktionen]] mit
- $f_n \uparrow f$

Das $\mu$-[[mu-Integral|Integral]] auf $f$ ist definiert als

$$
	\int f d\mu = \sup_{n \in \mathbb{N}} \int f_n d\mu
$$

---

Sei $f \in \mathcal{M}$.

$f$ hat ein *existierendes* $\mu$-[[mu-Integral|Integral]], falls
- $\int f^+ d\mu \lt \infty$ oder
- $\int f^- d\mu \lt \infty$

Das $\mu$-[[mu-Integral|Integral]] auf $f$ ist definiert als

$$
	\int f d\mu = \int f^+ d\mu - \int f^- d\mu
$$

Es gilt
- $|\int f d\mu| \le \int |f| d\mu$

---

Sei $f \in \mathcal{M}$.

$f$ heißt *$\mu$-integrierbar*, falls
- $\int f^+ d\mu \lt \infty$ und
- $\int f^- d\mu \lt \infty$

Das $\mu$-[[mu-Integral|Integral]] auf $f$ ist definiert als

$$
	\int f d\mu = \int f^+ d\mu - \int f^- d\mu
$$

---

Sei $f \in \mathcal{M}$.

$f$ $\mu$-integrierbar $\iff$ $|f|$ $\mu$-integrierbar.

---

Sie $f, g \in \mathcal{M}$ [[Funktion|messbare]] [[Funktion|Funktionen]] mit
- $|f| \le |g|$

$g$ $\mu$-integrierbar $\implies$ $f$ $\mu$-integrierbar