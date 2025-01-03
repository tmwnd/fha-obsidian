Sei $W \sim \chi_n^2$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $Z \sim \chi_m^2$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit
- $W, Z$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]]

Die Verteilung von $F := \frac{\frac{1}{n} W}{\frac{1}{m} Z}$ heißt *F-Verteilung* mit $n$ und $m$ Freiheitsgraden.

Es gilt
- $F$ hat die Dichte $f_{n, m}(x) = \left. \begin{cases} \frac{\Gamma(\frac{m+n}{2}) \cdot (\frac{m}{n})^\frac{m}{2} \cdot x^{\frac{m}{2}-1}}{\Gamma(\frac{m}{2}) \cdot \Gamma(\frac{n}{2}) \cdot (1 + \frac{m}{n}x)^\frac{m+n}{2}} \quad & x \gt 0 \\ 0 \quad & \text{sonst} \end{cases} \ \right| \ x \in \mathbb{R}$

Schreibe
- $T \sim F_{n, m}$