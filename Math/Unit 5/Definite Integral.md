$$\int^{b}_{a}f(x)dx$$
- b = Upper Bound
- a = Lower Bound
- $\int$ = integral sign
- $f(x)$ = function to be integrated
- $dx$ = variable that is being integrated
![[Definite Integral example 0 Picture 1]]
## Formal Definition
$$\int^{b}_{a}f(x)dx=\lim\limits_{n \rightarrow \infty}\sum^{n}_{k=1}f(a+k\frac{b-a}{n})(\frac{b-a}{n})$$

> [!NOTE] Note
> - Integrals represent accumulated change
> - Integrals are the area under a curve
## Integrability of continuous functions
If $f$ is continuous on $[a,b]$, or if $f$ has a finite number of jump discontinuities, then $\int^{b}_{a}f(x)$ exists and $f$ is integrable on $[a,b]$.

---
If $f(x)$ and $g(x)$ are integrable on $[a,b]$:
1. $$\int^{b}_{a}f(x)dx=-\int^{a}_{b}f(x)dx$$
2. $$\int^{a}_{a}f(x)dz=0$$
3. Where $k$ is a constant$$\int^{b}_{a}k*f(x)dx=k\int^{b}_{a}f(x)dx$$
4. $$\int^{b}_{a}(f(x)\pm g(x))dx=\int^{b}_{a}f(x)dx\pm\int^{b}_{a}g(x)dx$$
5. $$\int^{b}_{a}f(x)dx+\int^{c}_{b}f(x)dx=\int^{c}_{a}f(x)dx$$
## Area under the curve
The area below $y=f(x)$ on $[a,b]$ is $A=\int^{b}_{a}f(x)dx$
### Basic Definite Integrals
1. $$\int^b_axdx=\frac{b^2}{2}-\frac{a^2}{2}$$
2. $$\int^b_ax^2dx=\frac{b^3}{3}-\frac{a^3}{3}$$
3. $c$ is constant $$\int^b_acdx=c(b-a)$$