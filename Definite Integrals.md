$\int_{a}^{b}f\left(x\right)\mathrm{dx}$
Definite Integral -> of *f* from *a* to *b*
There needs to be [[Continuity]] on the closed interval $\left\lbrack a,b\right\rbrack$, then *f* is integrable on $\left\lbrack a,b\right\rbrack$. That is $\int_{a}^{b}f\left(x\right)\mathrm{dx}$ exists.

-----
**Properties of Definite Integrals**
1. If *f* is defined at $x=a$, then $\int_{b}^{a}f\left(x\right)\mathrm{dx}=0$.
	1. Since you are starting at a and moving towards a there is no distance so there is no area below the curve to be measured
2. If *f* is integrable on $\left\lbrack a,b\right\rbrack$, then $\int_{b}^{a}f\left(x\right)\mathrm{dx}=-\int_{a}^{b}f\left(x\right)\mathrm{dx}$
	1. A positive limit inverted and negative is equal to each other.

---
**Additive Interval Property**
If *f* is integrable on the three closed intervals determined by *a*, *b*, *c*, then
$\int_{a}^{b}f\left(x\right)\mathrm{dx}=\int_{a}^{c}f\left(x\right)\mathrm{dx}+\int_{c}^{b}f\left(x\right)\mathrm{dx}$

----
**Properties of Definite Integrals**
If *f* and *g* are integrable on $\left\lbrack a,b\right\rbrack$ and *k* is a constant, then the functions *kf* and $f\pm g$ are integrable on $\left\lbrack a,b\right\rbrack$, and
1. $\int_{a}^{b}kf\left(x\right)\mathrm{dx}=k\int_{a}^{b}f\left(x\right)\mathrm{dx}$
2. $\int_{a}^{b}\left\lbrack f\left(x\right)\pm g\left(x\right)\right\rbrack\mathrm{dx}=\int_{a}^{b}f\left(x\right)\mathrm{dx}\pm\int_{a}^{b}g\left(x\right)\mathrm{dx}$

----
Examples:
Evaluate $\int_1^3\left(-x^2+4x-3\right)$ using each of the following values.

1. $\int_1^3x^2\mathrm{dx}=\frac{26}{3}$
2. $\int_1^3x\mathrm{dx}=4$
3. $\int_1^3\mathrm{dx}=2$

After inserting into each function using the Additive Interval Property
$\frac{-26}{3}+16-6$

