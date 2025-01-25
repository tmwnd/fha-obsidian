| Verteilung | Momentenschätzer | Maximum-Likelihood-Schätzer |
|---|---|---|
| $\mathfrak{G}(a, y)$ | $\alpha = \frac{\text{E}[X_1]^2}{\text{Var}[X_1]}$, $\lambda = \frac{\text{E}[X_1]}{\text{Var}[X_1]}$ ||
| [[zettel/_examples/Laplaceverteilung\|Laplaceverteilung]] || $\hat{\mu}(X) \in [X_{\lceil \frac{n}{2} \rceil}, X_{\lfloor \frac{n}{2}+1 \rfloor}]$, $\hat{\sigma}(X) = \frac{1}{n} \sum_{i=1}^n \lvert x_i - \hat{\mu}(X) \rvert$ |
| [[zettel/_examples/Logistische Verteilung\|Logistische Verteilung]] || $\frac{\partial}{\partial a} \log(f(x, a)) = n - 2\sum_{i=1}^n \frac{e^{a-x_i}}{1 + e^{a-x_i}} \overset{!}{=} 0$ |
| $\mathcal{N}(\mu, \sigma^2)$ || $\hat{\mu}(X) = \frac{1}{n} \sum_{i=1}^n x_i$,  $\hat{\sigma}^2(X) =  \frac{1}{n} \sum_{i=1}^n (x_i - \hat{\mu}(X))^2$ |