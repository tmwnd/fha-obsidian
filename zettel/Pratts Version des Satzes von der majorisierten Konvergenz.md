Sei $f, g, G, (f_n)_{n \in \mathbb{N}}, (g_n)_{n \in \mathbb{N}}, (G_n)_{n \in \mathbb{N}} : (\Omega, \mathcal{A}) \to (\mathbb{R}, \mathscr{B})$ [[zettel/Funktion/Messbarkeit|messbar]] mit
- $\forall n \in \mathbb{N} : g_n \le f_n \le G_n$
- $\forall n \in \mathbb{N} : g_n, G_n$ sind $\mu$-[[zettel/Funktion/μ-Integrierbarkeit|integrierbar]]
- $g, G$ sind $\mu$-[[zettel/Funktion/μ-Integrierbarkeit|integrierbar]]
- $\liminf_{n \to \infty} f_n = f$
- $\lim_{n \to \infty} g_n = g$
- $\lim_{n \to \infty} G_n = G$
- $\lim_{n \to \infty} \int g_n d\mu = \int g d\mu$
- $\lim_{n \to \infty} \int G_n d\mu = \int G d\mu$

Dann ist $f$ $\mu$-[[zettel/Funktion/μ-Integrierbarkeit|integrierbar]] und es gilt

$$
	\lim_{n \to \infty} \int f_n d\mu = \int f d\mu
$$