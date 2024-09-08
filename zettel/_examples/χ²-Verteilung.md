Seien $(Z_i)_{i \in \{ 1, \dots, n \}} \sim \mathcal{N}(0, 1)$ [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängige]], identisch verteilte [[zettel/Zufallsvariable|Zufallsvariablen]].

$X := \sum_{i=1}^n Z_i^2$ heißt *Chi-Quadrat-verteilt* mit $n$ Freiheitsgraden.

Es gilt
- $X \sim \mathfrak{G}(\frac{n}{2}, \frac{1}{2})$
- $X$ hat die Dichte $f(x) = \left. \frac{x^{\frac{n}{2} - 1}}{2^{\frac{2}{2}}\Gamma(\frac{n}{2})} \exp\left( -\frac{1}{2}x \right) \ \right| \ x \gt 0$

Schreibe
- $X \sim \chi^2$