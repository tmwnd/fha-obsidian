Sei $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{IID}(0, \sigma^2)$, $\mu : [0, 1] \times \mathcal{L}(\Omega, \mathcal{A}, P)^p \to \mathbb{R}$ eine zeitabhängige Erwartungswertfunktion, $\sigma^2 : [0, 1] \times \mathcal{L}(\Omega, \mathcal{A}, P)^p \to \mathbb{R}^+$ eine zeitabhängige Varianzfunktion.

Ein [[zettel/Schema von Zufallsvariablen|Schema von Zufallsvariablen]] $((X_{T, t})_{t \in \mathbb{Z}, t \le T})_{T \in \mathbb{Z}}$ heißt *Zeitabhängiger Nichtlinearer Autoregressiver Prozess (tvNAR-Prozess)*, falls

$$
	\forall T, t \in \mathbb{Z}, t \le T : X_{T, t} = \mu\left( \frac{t}{T}, (X_{T, t-i})_{i \in \{ 1, \dots, p \}} \right) + \sigma\left( \frac{t}{T}, (X_{T, t-i})_{i \in \{ 1, \dots, p \}} \right) \varepsilon_t
$$

Es gilt
- $((X_{T, t})_{t \in \mathbb{Z}, t \le T})_{T \in \mathbb{Z}}$ ist unter schwachen Annahmen [[zettel/Zeitreihe/Lokale Stationarität|lokal stationär]]