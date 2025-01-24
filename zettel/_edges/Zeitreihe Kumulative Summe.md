Sei $(X_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] und
- $(Y_t)_{t \in \mathbb{Z}}$ eine [[zettel/Zeitreihe|Zeitreihe]] definiert als

$$
	\forall t \in \mathbb{Z} : Y_t := \nabla X_t
$$

Der *kumulative Summe* $(\hat{X}_t)_{t \in \mathbb{Z}}$ von $(Y_t)_{t \in \mathbb{Z}}$ ist ein Schätzer für $(X_t)_{t \in \mathbb{Z}}$ und definiert als

$$
	\forall t \in \mathbb{Z} : \hat{X}_t := \sum_{i=0}^t Y_i
$$

Es gilt
- $\exists c \in \mathbb{R} \ \forall t \in \mathbb{Z} : X_t = \hat{X}_t + c$