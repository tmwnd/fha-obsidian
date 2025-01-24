Sei $\{ (X_t^{(u)})_{t \in \mathbb{Z}} \}_{u \in [0, 1]}$ eine Familie [[zettel/Zeitreihe/Starke Stationarität|stark stationärer]] [[zettel/Zeitreihe|Zeitreihen]], $\{ P_{T, t}^{(u)} \mid T, t \in \mathbb{N}, t \le T, u \in [0, 1] \}$ eine Menge reellwertiger [[zettel/Zufallsvariable|Zufallsvariablen]].

Ein [[zettel/Schema von Zufallsvariablen|Schema von Zeitreihen]] $((X_{t, T})_{t \in \mathbb{Z}, t \le T})_{T \in \mathbb{Z}}$ heißt *lokal stationär nach Vogt*, falls

$$
	\forall T, t \in \mathbb{N}, t \le T, u \in [0, 1] :  |X_{T, t} - X_t^{(u)}| \le \left(\left| \frac{t}{T} - u \right| + \frac{1}{T} \right) P_{t, t}^{(u)}
$$