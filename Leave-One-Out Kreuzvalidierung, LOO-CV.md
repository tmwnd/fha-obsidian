Sie $\mathcal{D}$ ein [[Datensatz]] mit
- $N = |\mathcal{D}|$
- $\mathcal{D}_i = \mathcal{D} \setminus (x_i, y_i) = \{ (x_1, y_1), \dots, (x_{i-1}, y_{i-1}), (x_{i+1}, y_{i+1}), \dots, (x_N, y_N) \}$
- $g_i^-$ die finale [[Hypothese]] auf $D_i$
- $E_\text{val}(g_i^-)$ der [[In-Sample Error]] auf $g_i^-$

Der *Kreuzvalidierungsfehler* $E_\text{CV}$ ist definiert als

$$
	E_\text{CV}(g^-) = \frac{1}{N} \sum_{i=1}^N E_\text{val}(g_n^-) \approx E_\text{out}(g^-)
$$