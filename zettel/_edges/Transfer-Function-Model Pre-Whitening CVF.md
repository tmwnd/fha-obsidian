Sei $(X_t)_{t \in \mathbb{Z}} \sim \text{ARMA}(p, q)$ von $(\varepsilon_t)_{t \in \mathbb{Z}} \sim \text{WN}(0, \sigma^2)$ [[zettel/ARMA-Prozess/Kausale Abhängigkeit|kausal abhängig]] und [[zettel/ARMA-Prozess/Invertierbarkeit|invertierbar]], $(Y_t)_{t \in \mathbb{Z}}$ ein [[zettel/Transfer-Function-Model|Transfer-Function-Model]] von $(X_t)_{t \in \mathbb{Z}}$, $(X_t^*)_{t \in \mathbb{Z}}$ bzw. $(Y_t^*)_{t \in \mathbb{Z}}$ die [[zettel/Pre-Whitening-Transformation|Pre-Whitening-Transformation]] von $(X_t)_{t \in \mathbb{Z}}$ bzw. $(Y_t)_{t \in \mathbb{Z}}$ von  mit
- $\forall t \in \mathbb{Z} : \text{E}[X_t] = 0$
- $\forall t \in \mathbb{Z} : \text{E}[Y_t] = 0$
- $\forall t \in \mathbb{Z} : \text{E}[X_t^*] = 0$
- $\forall t \in \mathbb{Z} : \text{E}[Y_t^*] = 0$

Die [[CVF]] $\gamma_{Y^*, X^*} : \mathbb{Z}^2 \to \mathbb{R}$ ist gegeben durch

$$
	\gamma_{Y^*, X^*}(h) = \beta_h \sigma^2
$$

und
- $\gamma_{Y^*, X^*}(h)$ beschreibt den kausalen Zusammenhang von $(X_t)_{t \in \mathbb{Z}}$ und $(Y_t)_{t \in \mathbb{Z}}$
- $(X_t^*)_{t \in \mathbb{Z}} \not\sim \text{WN}(0, \sigma)$, falls $(X_t)_{t \in \mathbb{Z}}$ und $(Y_t)_{t \in \mathbb{Z}}$ kausal abhängig sindy
- $\nu \approx \underset{h \in \mathbb{Z}}{\arg\min} \ \mathbb{1}(|\gamma_{Y^*, X^*}(h)| \gg 0)$