Seien $(X_n)_{n \in \mathbb{N}}$, $X$ reelle [[zettel/Zufallsvariable|Zufallsvariablen]] mit
- $\forall j \in \mathbb{N} : \text{E}\left[ |X|^j \right] \lt \infty$
- $\forall n, j \in \mathbb{N} : \text{E}\left[ |X_n|^j \right] \lt \infty$

Es gilt

$$
	\forall j \in \mathbb{N} : \lim_{n \to \infty} \text{E}\left[ X_n^j \right] = \text{E}\left[ X^j \right] \implies X_n \overset{V}{\longrightarrow} X
$$