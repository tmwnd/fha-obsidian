Sei $(\varepsilon_t)_{t \in \mathbb{Z}}$ eine Folge [[zettel/Zufallsvariable/Stochastische Unabhängigkeit|unabhängiger]] und identisch verteilter [[zettel/Zufallsvariable|Zufallsvariablen]] und
- $(\mathcal{F}_t)_{t \in \mathbb{Z}}$ eine [[zettel/Filtration|Filtration]] definiert als

$$
	\forall t \in \mathbb{Z} : \mathcal{F_t} := (\varepsilon_s)_{s \in \mathbb{Z}, s \le t}
$$

Ein [[zettel/Schema von Zufallsvariablen|Schema von Zeitreihen]] $((X_{t, T})_{t \in \mathbb{Z}, t \le T})_{T \in \mathbb{Z}}$ heißt *lokal stationär nach Zhou und Wu*, falls

$$
	\exists G : [0, 1] \times \mathbb{R}^\mathbb{N} \to \mathbb{R} \ \forall T, t \in \mathbb{N}, t \le T : X_{T, t} = G\left( \frac{t}{T}, \mathcal{F}_t \right)
$$