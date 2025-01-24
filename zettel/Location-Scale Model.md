Sei $(\varepsilon_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe/Schwache Stationarität|schwach stationäre]] [[zettel/Zeitreihe|Zeitreihe]], $\mu, \sigma : [0, 1] \to \mathbb{R}$ stetig und
- $((X_t)_{t \in \mathbb{N}, t \le T})_{T \in \mathbb{N}}$ ein [[zettel/Schema von Zufallsvariablen|Schema von Zeitreihen]] definiert als

$$
	\forall T, t \in \mathbb{N}, t \le T : X_{T, t} := \mu\left( \frac{t}{T} \right) + \sigma\left( \frac{t}{T} \right) \varepsilon_t
$$

Es gilt
- $\forall T \in \mathbb{N} : (X_t)_{t \in \{ 1, \dots, t \}}$ ist nicht-[[zettel/Zeitreihe/Schwache Stationarität|schwach stationär]]
- $((X_t)_{t \in \mathbb{N}, t \le T})_{T \in \mathbb{N}}$ ist [[zettel/Zeitreihe/Lokale Stationarität|lokal staionär]]