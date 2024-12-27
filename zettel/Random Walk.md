Sei $(\epsilon_t)_{t \in \mathbb{N}} \sim \text{IID}(0, \sigma^2)$ ein [[zettel/IID-Rauschen|IID-Rauschen]].

Die Zeitreihe $(X_t)_{t \in \mathbb{N}}$ heißt *Random Walk* und ist definiert als

$$
	\forall t \in \mathbb{N} : X_t = \sum_{i=1}^t \epsilon_i
$$

Es gilt
- $\forall t \in \mathbb{N} : \text{E}[X_t] = \sum_{i=1}^t \text{E}[\epsilon_i] = 0$
- $\forall t \in \mathbb{N} : \text{Var}[X_t] = \sum_{i=1}^t \text{Var}[\epsilon_i] = t \cdot \sigma^2$