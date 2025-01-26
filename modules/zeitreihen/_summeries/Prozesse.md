| Prozess | Schreibe | [[zettel/Zeitreihe/Schwache Stationarität\|schwach stationär]] | [[zettel/Kovarianzfunktion\|Kovarianzfunktion]] $\gamma(t, s)$ | [[zettel/ACVF\|ACVF]] $\gamma(h)$ | [[zettel/ACF\|ACF]] $\rho(h)$ | [[zettel/PACF\|PACF]] $\tau(h)$ |
|---|---|---|---|---|---|---|
| [[zettel/Weißes Rauschen\|Weißes Rauschen]] | $\text{WN}(0, \sigma^3)$ | ja  |||||
| [[zettel/IID-Rauschen\|IID-Rauschen]] | $\text{IID}(0, \sigma^2)$ | ja || $\sigma^2 \cdot \mathbb{1}(h = 0)$ | $\mathbb{1}(h = 0)$ ||
| [[zettel/Gauß'sches Weißes Rauschen\|Gaußsches weißes Rauschen]] | $\text{GWN}(0, \sigma^2)$ ||||||
| [[zettel/Random Walk\|Random Walk]] || nein | $t \cdot \sigma^2$ |/|/|/
| [[zettel/AR-Prozess erster Ordnung\|AR-Prozess erster Ordnung]] | $\text{AR}(1)$ | ja | siehe ACVF | $\frac{\sigma^2}{1 - \phi^2} \cdot \phi^{\lvert h \rvert}$ | $\phi^{\lvert h \rvert}$ | $\begin{cases} \alpha = \rho(1) & h = 1 \\ 0 & h \gt 1 \end{cases}$ |
| [[zettel/AR-Prozess\|AR-Prozess]] | $\text{AR}(p)$ |
| [[zettel/MA-Prozess erster Ordnung\|MA-Prozess erster Ordnung]] | $\text{MA}(1)$ | ja | siehe ACVF | $\begin{cases} \sigma^2 \cdot (1 + \vartheta^2) & h = 0 \\ \sigma^2 \cdot \vartheta & h \in \{ -1, 1 \} \\ 0 & \text{sonst} \end{cases}$
| [[zettel/MA-Prozess\|MA-Prozess]] | $\text{MA}(q)$ | ja | siehe ACVF | $\begin{cases} \sum_{i=0}^{q-\lvert h \rvert} \vartheta_i\vartheta_{i+\lvert h \rvert} & \lvert h \rvert \le q \\ 0 & \lvert h \rvert \gt q \end{cases}$
| [[zettel/ARMA-Prozess\|ARMA-Prozess]] | $\text{ARMA}(p, q)$ |
| [[zettel/Linearer Prozess\|Linearer Prozess]] || ja | $\sigma^2 \sum_{i \in \mathbb{Z}} \psi_i\psi_{i-h}$ | $\sum_{i \in \mathbb{Z}} \sum_{j \in \mathbb{Z}} \psi_i\psi_j \text{E}[\varepsilon_{h+i-j}]$