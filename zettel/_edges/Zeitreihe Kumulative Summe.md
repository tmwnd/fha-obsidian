Sei $(X_t)_{t \in \mathbb{N}}$ eine [[zettel/Zeitreihe|Zeitreihe]] und
- $(Y_t)_{t \in \mathbb{N}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert als

$$
	\forall t \in \mathbb{N} : Y_t := \nabla X_t
$$

Der *kumulative Summe* $(\hat{X}_t)_{t \in \mathbb{N}}$ von $(Y_t)_{t \in \mathbb{N}}$ ist ein Schätzer für $(X_t)_{t \in \mathbb{N}}$ und definiert als

$$
	\forall t \in \mathbb{N} : \hat{X}_t := \sum_{i=0}^t Y_i
$$

Es gilt
- $\exists c \in \mathbb{R} \ \forall t \in \mathbb{N} : X_t = \hat{X}_t + c$