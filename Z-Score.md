Sei $X$ ein [[Datensatz]].

Der *Z-Score* $Y$ von $X$ ist mit [[Erwartungswert]] $E$ und [[Varianz]] Var definiert als

$$
	z = \frac{x - E[X]}{\text{Var}(X)}
$$

---

```py
Z = (X - X.mean(axis=0)) / X.std(axis=0)
```