Sei $X, y$ ein [[Datensatz]], $h$ eine [[Hypothese]], $c$ Koeffizienten mit
- $K_n = \{ x_i \in X \mid I_n(x_i) = 1 \}$
- [[Lineare Regression]]:
	- $\forall n \in \{ 1, \dots, |X| \} : c_n = \frac{1}{|K_n|}\sum_{y_i \in K_n} y_n$
- Klassifikation:
	- $\forall n \in \{ 1, \dots, |X| \} : c_n$ Mehrheitslabel von $K_n$

$h$ ist durch einen *Baum* mit der [[Indikatorfunktion]] $I_m$ definiert als

$$
	h(x) = \sum_{m=1}^M c_mI_m(x)
$$