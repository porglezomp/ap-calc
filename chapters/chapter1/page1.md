---
chapter: 1
title: Definition of Limits
---

### Informal Definition

Limits can be informally defined as the value $L$ that a function $f(x)$ approaches as its independent variable $x$ approaches another value $a$. As $x$ gets closer and closer to $a$, $f(x)$ gets closer and closer to $L$. This can be written in limit notation as follows:

$$
\lim_{x \rightarrow a} f(x) = L
$$

Limits are useful because they can be used to find beahvior near points which aren't evaluatable. For instance, the function $f(x) = \frac{x}{x}$ is equal to 1 everywhere but $x = 0$, where it's undefined. The fact that

$$
\lim_{x \rightarrow 0} f(x) = 1
$$

tells us that near $x = 0$, the function evaluates to 1, and can be used to redefine the function at the hole.

### Formal Definition

A limit $\lim_{x \rightarrow a} f(x) = L$ can be formally proven to exist if for every $\varepsilon > 0$ there is a $\delta > 0$ such that

$$
 0 < \left|\ x-a \right| < \delta \implies \left|\ f(x) - L\right| < \varepsilon 
$$