Sei $\mathcal{D}$ ein [[Datensatz]], $\mathcal{H}$ ein [[Hypothese|Hypothesenset]].

Der *Bruchpunkt* $k$ ist definiert als die kleinste Anzahl an Datenpunkten aus $\mathcal{D}$, welche **nicht** durch $\mathcal{H}$ [[Dichotomie|zerbrochen]] werden können.

---

Sei $\mathcal{D}$ ein [[Datensatz]], $\mathcal{H}$ ein [[Hypothese|Hypothesenset]].

$k$ ist ein Bruchpunkt für $\mathcal{H}$, falls
- die [[Wachstumsfunktion]] $m_\mathcal{H}(k) \lt 2^k$

Es gilt
- $\forall N \in \{ 1, \dots, |\mathcal{D}| \} : m_\mathcal{H}(N) \le N^{k-1} + 1$
- $\forall N \in \{ 1, \dots, |\mathcal{D}| \} : m_\mathcal{H}(N) \le \sum_{i=0}^{k-1} \binom{N}{i}$

---

Sei $\mathcal{D}$ ein [[Datensatz]], $\mathcal{H}$ ein [[Hypothese|Hypothesenset]].

Es gibt **keinen** Bruchpunkt für $\mathcal{H}$, falls für die [[Wachstumsfunktion]]  $m_\mathcal{H}$ gilt
- $\forall N \in \{ 1, \dots, |\mathcal{D}| \} : m_\mathcal{H}(N) = 2^N$