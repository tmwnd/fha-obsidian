1. Die diskrete Verteilung des $\{ -1, 0, 1 \}^2$-wertigen $2$-dimensionalen Zufallsvektors $(X, Y)$ sei festgelegt durch die in der nachfolgenden Tabelle genannten Werte $p_{xy} = P(X = x, Y = y)$.
	
	$$
	\begin{array}{cc|ccc}
		&&& y \\
		&& -1 & 0 & 1 \\\hline
		& -1 & \frac{1}{8} & 0 & \frac{1}{16} \\
		y & 0 & 0 & \frac{1}{2} & 0 \\
		& 1 & \frac{3}{16} & 0 & \frac{1}{8}
	\end{array}
	$$
	
	Bestimmen Sie
	- a) $E(X)$, $E(Y)$ und $E(X + Y)$
	- b) $E(XY)$

^1

2. Die reele Zufallsvariable sei exponentialverteilt mit dem Parameter $\lambda \gt 0$.
	Es sei $Y = e^{-2X}$ und $Z = \min(X, \frac{1}{\lambda})$.
	Bestimmen Sie die Erwartungswerte $E(Y)$ und $E(Z)$.

^2

3. Der Radarschirm der Rundsichtanlage einer Navigationsstation ist eine Kreisscheibe mit dem Radius $a \gt 0$.
	Infolge von Störungen kann ein Fleck auf dem Radarschirm auftreten, von dem angenommen wird, dass dessen Koordinaten sich durch eine Zufallsvariable Beschreiben lassn, die auf der Kreisscheibe gleichverteilt ist.
	Bestimmen Sie den Erwartungswert und die Varianz des Abstandes des Fleckenzentrums zum Kreismittelpunkt.

^3

- a) Wiederholt wird aus einer Urne, die $n \ge 3$ mit den Zahlen von $1$ bis $n$ durchnummerierte Kugeln enthält, je eine Kugel gezogen und wieder in die Urne zurückgelegt.
	Die Zufallsvariable $X_n$ bezeichne die Nummer des Zuges, bei dem die Zahl der gezogenen Kugel zum ersten Mal mit der Zahl einer bereits gezogenen Kugel übereinstmimmt.
	Gezeigt werden soll:
	- 1) $P(X_n = r) = (1 - \frac{1}{n}) \dots (1 - \frac{r-2}{n}) (1 - \frac{r-1}{n}), \quad r \gt 2$
	- 2) $E(X_n) = \sum_{r=0}^n \binom{n}{r} \frac{r!}{n^r} = \int_0^\infty (1 + \frac{x}{n})^ne^{-x} dx$
	- 3) $\lim_{n \to \infty} \frac{E(X_n)}{\sqrt{\frac{n\pi}{2}}} = 1$
	
	*Hinweis:* Verwende (2) und die Ungleichung $\log(1+t) \ge t - \frac{1}{2}t^2$ für $t \ge 0$ bzw. $1 - t \le r^{-t}$ für $t \in \mathbb{R}$ für eine entsprechende Abschätzung des Erwartungswertes $E(X_n)$ nach unten bzw. oben.

- b) Beurteilt werden soll die folgende Pressemitteilung vom 29.06.1995:
  
  > [!tldr] Erstmals im Lotto dieselbe Zahlenreihe
  > **Stuttgart** (dpa/lsw). Die Staatliche Toto-Lotto GmbH in Stuttgart hat eine Lottosensation gemeldet: Zum ersten Mal in der 40jährigen Geschichte des deutschen Zahlenlottos wurden zwei identische Gewinnreihen festgestellt. Am 21. Juni dieses Jahres kam im Lotto am Mittwoch in der Ziehung A die Gewinnreihe 15,25,27,30,42,48 heraus. Genau dieselben Zahlen wurden bei der 1628. Ausspielung im Samstagslotto schon einmal gezogen, nämlich am 20. Dezember 1988. Welch ein Lottozufall: Unter der 49 Zahlen sind fast 14 Millionen verschiedene Sechserreihen möoglich.

  Bis zum 21.06.1995 gab es $2071$ Ausspielungen im Samstagslotto und $2 \cdot 427$ Ausspielungen im Mittwochslott (je A und B).

^4