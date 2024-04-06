---
type: solution
---

![[psets/sto1/assignment 02#^1]]

---

![[psets/sto1/assignment 02#^2]]

---

![[psets/sto1/assignment 02#^3]]

$G$ ist eine [[Verteilungsfunktion]], falls
1. $G$ monoton wachend ist
2. $G$ rechtsseitig stetig ist
3. $\lim_{x \to -\infty} G(x) = 0$
4. $\lim_{x \to +\infty} G(x) = 1$

Alle Voraussetzungen sind erfüllt, da
1. Sei $(x_n)_{n \to \mathbb{N}} \downarrow x$.
	$\lim_{n \to \infty} F(x_n) = F(x) \implies \lim_{n \to \infty} \frac{1}{h}\int_{x_n}^{x_n+h} F(d) dt = \frac{1}{h}\int_{x}^{x+h} F(t) dt \implies \lim_{n \to \infty} G(x_n) = G(x)$
2. $x_1 \le x_2 \implies F(x_1) \le F(x_2) \implies \frac{1}{h}\int_{x_1}^{x_1+h} F(t) dt \le \frac{1}{h}\int_{x_1}^{x_1+h} F(t) dt \implies G(x_1) \le G(x_2)$
3. $\lim_{x \to -\infty} G(x) = \lim_{x \to -\infty} \frac{1}{h}\int_{x}^{x+h} F(x) dt \ge \lim_{x \to -\infty} \frac{1}{h}\int_{x}^{x+h} 0 dt = 0$
4. $\lim_{x \to +\infty} G(x) = \lim_{x \to +\infty} \frac{1}{h}\int_{x}^{x+h} F(x) dt \le \lim_{x \to +\infty} \frac{1}{h}\int_{x}^{x+h} 1 dt = \frac{1}{h}h = 1$

---

![[psets/sto1/assignment 02#^4]]