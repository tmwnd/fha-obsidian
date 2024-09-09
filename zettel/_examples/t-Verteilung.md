Sei $V \sim \mathcal{N}(0, 1)$ eine [[zettel/Zufallsvariable|Zufallsvariable]], $Z \sim \chi_n^2$ eine [[zettel/Zufallsvariable|Zufallsvariable]] mit
- $V, Z$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängig]]

Die Verteilung von $T := \frac{V}{\sqrt{\frac{1}{n} Z}}$ heißt *t-Verteilung* mit $n$ Freiheitsgraden.

Es gilt
- $T$ hat die Dichte $f_n(x) = \left. \frac{1}{\sqrt{n\pi}} \cdot \frac{\Gamma(\frac{n+1}{2})}{\Gamma(\frac{n}{2})} \cdot \left( 1 + \frac{x^2}{n} \right)^{-\frac{n+1}{2}} \ \right| \ x \in \mathbb{R}$

Schreibe
- $T \sim t_n$