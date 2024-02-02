Sei $(\Omega, \mathcal{A})$ ein [[Messraum]], $\mu$ ein [[Maß]] auf $\mathcal{A}$, $f \in \mathcal{P}_+$ eine [[Funktion|primitive]] [[Funktion]] in [[Funktion|Normalendarstellung]] mit $(\alpha_i)_{i \in \{ 1, \dots, n \}} \in \mathbb{R}_+$.

Das *$\mu$-Integral* ist wohldefiniert als

$$
	\int f d\mu = \sum_{i=1}^n \alpha_i\mu(A_i)
$$

---

Es gilt
- $\forall A \in \mathcal{A} : \int I_A d\mu = \mu(A)$
- $\forall f \in \mathcal{P}_+, \alpha \in \mathbb{R}_+ : \int \alpha f d\mu = \alpha \int f d\mu$
- $\forall f, g \in \mathcal{P}_+ : \int (f + g) d\mu = \int f d\mu + \int g d\mu$
- $\forall f, g \in \mathcal{P}_+, \alpha, \beta \in \mathbb{R} : \int (\alpha f + \beta g) d\mu = \alpha \int f d\mu + \beta \int g d\mu$
- $\forall f, g \in \mathcal{P}_+, f \le g : \int f d\mu \le \int g d\mu$

---

Das $\mu$-Integral ist ein *positives* *lineares* *Funktional* auf dem reelen Vektorraum $\mathcal{L}(\Omega, \mathcal{A}, \mu) = \{ f \text{ reelwertig, messbar, } \mu \text{-integreirbar } \}$.