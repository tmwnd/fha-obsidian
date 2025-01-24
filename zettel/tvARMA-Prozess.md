Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{GWN}(0, 1)$, $\sigma^2 : [0, 1] \to \mathbb{R}^+$ eine zeitabhängige Varianzfunktion, $(\phi_i)_{i \in \{ 1, \dots p \}}, (\vartheta_i)_{i \in \{ 1, \dots, q \}} : [0, 1] \to \mathbb{R}$ zeitabhängige AR- bzw. MA-Koeffizientenfunktionen.

Ein [[zettel/Schema von Zufallsvariablen|Schema von Zeitreihen]] $((X_{t, T})_{t \in \mathbb{N}, t \le T})_{T \in \mathbb{N}}$ heißt *Zeitabhängiger Autoregressiver Moving Average Prozess (tvARMA-Prozess) der Ordnungen $p$ und $q$*, falls

$$
	\forall T, t \in \mathbb{Z}, t \le T : X_{T, t} - \sum_{i=1}^p \phi_i\left( \frac{t}{T} \right) X_{T, t-i} = \sigma\left( \frac{t}{T} \right) \varepsilon_t + \sum_{i=1}^q \vartheta_i\left( \frac{t}{T} \right) \varepsilon_{T, t-i}
$$

Schreibe

$$
	((X_{t, T})_{t \in \mathbb{N}, t \le T})_{T \in \mathbb{N}} \sim \text{tvARMA}(p, q)
$$

Es gilt
- $((X_{t, T})_{t \in \mathbb{N}, t \le T})_{T \in \mathbb{N}}$ ist [[zettel/Zeitreihe/Lokale Stationarität|lokal stationär]], falls $\sigma^2$, $\forall i \in \{ 1, \dots, p \} : \phi_i$ und $\forall i \in \{ 1, \dots, q \} : \vartheta_i$ stetig sind