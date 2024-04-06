---
title: Satz der majorisierten Konvergenz
type: theorem
aliases:
  - Satz von Henri Lebesgue
---

Sei $f, g, (f_n)_{n \in \mathbb{N}} \in \mathcal{M}$ [[Funktion messbar|messbare]] [[Funktion|Funktionen]] mit
- $g \ge 0$
- $\forall n \in \mathbb{N} : |f_n| \le g$
- $lim_{n \to \infty} f_n = f$
- $g$ ist $\mu$-[[μ-Integrierbarkeit|integrierbar]]

Es gilt für das $\mu$-[[μ-Integral|Integral]]
- $f, (f_n)_{n \in \mathbb{N}}$ sind $\mu$-[[μ-Integrierbarkeit|integrierbar]]
- $\lim_{n \to \infty} \int |f_n - f| d\mu = 0$
- $\lim_{n \to \infty} \int f_n d\mu = \int f d\mu$