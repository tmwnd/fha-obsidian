Sei $\mathcal{H}$ ein [[Hypothese|Hypothesenset]].

Die *VC Dimension* $d_{VC}$ von $\mathcal{H}$ ist definiert als der größte Wert $N$, für den gilt
- Die [[Wachstumsfunktion]] $m_\mathcal{H}(N) = 2^N$

$d_{VC}(\mathcal{H}) = \infty$, falls für die [[Wachstumsfunktion]]  $m_\mathcal{H}$ gilt
- $\forall N \in \{ 1, \dots, |\mathcal{D}| \} : m_\mathcal{H}(N) = 2^N$

---

Sei $\mathcal{H}$ ein [[Hypothese|Hypothesenset]], $k$ der [[Bruchpunkt]] von $\mathcal{H}$.

Es gilt
- $d_{VC}(\mathcal{H}) = k - 1$

---

Die VC Dimension entspricht der Anzahl freier, effektiver Parameter eines [[Hypothese|Hypothesensets]].