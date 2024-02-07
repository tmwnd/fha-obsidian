Durch Umformen der [[Hoeffding Ungleichung]] erhalten wir eine implizite Schranke für die benötigte Anzahl von Datenpunkten $N$, um eine Toleranz $\epsilon$ nicht zu überschreiten.

Es gilt

$$
	N \ge \frac{8}{\epsilon^2} \ln{(\frac{4((2N)^{d_{VC}}+1)}{\delta})}
$$

---

Eine *heuristische* [[Generalisierung]] ist mit der [[Vapnik-Chervonenkis Dimension, VC Dimension|VC Dimension]] definiert mit

$$
	N \ge 10 \cdot d_{VC}
$$