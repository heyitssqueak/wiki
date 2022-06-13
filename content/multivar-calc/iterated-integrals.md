---
title: Iterated Integrals
---

# what is an iterated integral?
An iterated integral is a set of integrals (usually [[🧲 double integrals]] or [[🧲 triple integrals]]) with bounds. 
> $$\int_a^b\int_c^d f(x,y)\, dy \, dx$$

Given the example of a double iterated integral, we can break it down into *two single  integrals* to evaluate. Since the inner integral is with respect to $y$, we first integrate with respect to $y$ while holding the $x$ variable fixed. Then, integrate the answer of the inner $y$ integral with respect to $x$.

#### ex:1
Given a function $A(x)$ being a single integral of $f(x,y) = x^2y$ with respect to $y$
> $A(x) = \int_0^2 x^2y \, dy$

We can integrate $A(x)$ with respect to $x$
> $\int_1^3 A(x)\, dx = \int_1^3\bigl[ \int_0^2 x^2y\, dy\bigr]dx$

Which gives us the form of a double iterated integral
> $\int_1^3 \int_0^2x^2y\, dy\, dx$

Evaluating the inner integral we get
 $\int_1^3 \bigl[ \frac{1}{2}x^2y^2 \Big|_{y=0}^{y=2} \,\bigr]\, dx$
 
 $\int_1^3 \bigl[ \frac{1}{2}4x^2\bigr]\, dx$
 
 $\int_1^3 2x^2\, dx$
 
 $\frac{2}{3}x^3\Big|_{x=1}^{x=3}$

>$\frac{2}{3} (3^3 - 3^1) = \frac{2}{3}(9-3) = 4$


---
## real numbers as bounds
If all bounds of the iterated integral are real numbers, then [[Fubini's theorem]] can be applied. The order of integration can be changed while still producing the same answer.
- formulas as bounds
- changing bounds