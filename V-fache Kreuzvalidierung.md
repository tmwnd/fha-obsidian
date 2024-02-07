Sie $\mathcal{D}$ ein [[Datensatz]], $V \in \mathbb{N}$ mit
- $N = |\mathcal{D}|$
- $(\mathcal{D}_v)_{v \in \{ 1, \dots, V \}} \subset \mathcal{D}$
- $\mathcal{D}_v = \mathcal{D} \setminus \mathcal{D}_v$
- $g_v^-$ die finale [[Hypothese]] auf $D_v$
- $E_\text{val}(g_v^-)$ der [[In-Sample Error]] auf $g_v^-$

Der *Kreuzvalidierungsfehler* $E_\text{V-fold CV}$ ist definiert als

$$
	E_\text{V-fold CV}(g^-) = \frac{1}{V} \sum_{v=1}^V E_\text{val}(g_v^-) \approx E_\text{out}(g^-)
$$