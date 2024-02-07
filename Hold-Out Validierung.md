Sie $\mathcal{D}$ ein [[Datensatz]].

Um den [[Out-Sample Error]] $E_\text{out}$ zu schätzen, wird $\mathcal{D}$ aufgeteilt in $\mathcal{D}_\text{train}$ und $\mathcal{D}_\text{val}$ mit
- $g^-$ die finale [[Hypothese]] auf $\mathcal{D}_\text{train}$
- $K = |\mathcal{D}_\text{val}|$
- $E_\text{val}(g^-) = E_\text{in}(g^-)$ der [[In-Sample Error]] auf $\mathcal{D}_\text{val}$

Es gilt nach [[Hoeffding Ungleichung]]

$$
	E_\text{out}(g^-) = E_\text{val}(g^-) + O(\frac{1}{\sqrt{K}})
$$

---

```py
from sklearn.model_selection import train_test_split
```

```py
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=.25)
```