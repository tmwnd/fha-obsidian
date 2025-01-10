Sei $(X_t)_{t \in \{ 1, \dots, n \}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $T$ die Anzahl von [[zettel/_edges/Zeitreihe Wendepunkt|Wendepunkten]] von $(X_t)_{t \in \mathbb{Z}}$, $\text{H} : (X_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2), \text{K} : (X_t)_{t \in \mathbb{Z}} \not\sim \text{WN}(0, \sigma^2)$.

Es gilt
- $\text{E}[T] = \frac{2}{3}(n-2)$
- $\text{Var}[T] = \frac{16n - 29}{90}$
- $n$ genügend groß $\implies$ $P \overset{V}{\approx} \mathcal{N}(\text{E}[T], \text{Var}[T])$

und
- $\forall t \in \{ 1, \dots, n \} : P(t \text{ ist ein Wendepunkt}) = \frac{1}{2}$, falls $\text{H}$ gültig ist

Verwerfe $\text{H}$, falls

$$
	\frac{|T - \text{E}[T]|}{\sqrt{\text{Var}[T]}} \gt \Psi_{1-\frac{\alpha}{2}}
$$