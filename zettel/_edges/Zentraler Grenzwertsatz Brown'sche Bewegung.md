Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]], $(B_n(u))_{n \in \mathbb{N}} \in \ell^\infty([0, 1])$, $B$ eine [[zettel/Wiener Prozess|Brown'sche Bewegung]] mit

$$
	\forall n \in \mathbb{N}, u \in [0, 1] : B_n(u) := \frac{1}{n} \sum_{s=1}^{\lfloor un \rfloor} X_s - \text{E}[X_s]
$$

Es gilt

$$
	(\sqrt{n} B_n(u))_{u \in [0, 1]} \overset{V}{\longrightarrow} \tilde{\sigma}B
$$