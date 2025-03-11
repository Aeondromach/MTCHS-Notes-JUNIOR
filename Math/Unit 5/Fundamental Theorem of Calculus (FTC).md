1. Part 1:
	If $f(x)$ is continuous on $[a,b]$, then $F(x)=\int^{x}_{a}f(t)dt$ is continuous on $[a,b]$ and differentiable on $(a,b)$. The derivative is $f(x)$
		$$F^1(x)=\frac{d}{dx}\int^{x}_{a}f(t)dt=f(x)$$
#### Example
Find $\frac{dy}{dx}$ if $y=\int^{x}_{a}(t^3+1)dt$
> $$\frac{dy}{dx}=\frac{d}{dx}\int^{x}_{a}t^3+1dt$$
> $$\frac{dy}{dx}=x^3+1$$
2. Part 2:
	If $f$ is continuous over $[a,b]$ and $F$ is any anti-derivative (integral) of $f$ on $[a,b]$, the: 
	$$\int^{b}_{a}f(x)=F(b)-F(a)$$
#### Example
$\int^{\pi}_{0}cos(x)dx$
> $$f^1(x)=cos(x) \rightarrow f(x)=sin(x)$$
> $$f(x)=cos(x) \rightarrow F(x)=sin$$
> $$\int^{\pi}_{0}cos(x)dx=sin(x)|^\pi_0$$
> $$sin(x)|^\pi_0=sin(\pi)-sin(0)=0-0=0$$
> $$\int^\pi_0cos(x)dx=0$$
#### Example
$\int^4_1\frac{3}{2}\sqrt{x}-\frac{4}{x^2}dx$
> $$\int^4_1\frac{3}{2}\sqrt{x}dx-\int^4_1\frac{4}{x^2}dx=$$
> $$\int^4_1\frac{3}{2}x^\frac{1}{2}dx-\int^4_14x^{-2}dx=$$
> $$f(x)=\frac{3}{2}x^\frac{1}{2}~||~f(x)=4x^{-2}$$
> $$F(x)=x^\frac{3}{2}~||~F(x)=-4x^{-1}$$
> $$x^\frac{3}{2}|^4_1-(-4x^{-1}|^4_1)$$
> $$x^\frac{3}{2}|^4_1+\frac{4}{x}|^4_1$$
> $$(4^\frac{3}{2}-1^\frac{3}{2}+(\frac{4}{4}-\frac{4}{1})$$
> $$=4\sqrt{4}-1+1-4$$
> $$=4\sqrt{4}-4$$
> $$=8-4$$
> $$=4=\int^4_1\frac{3}{2}\sqrt{x}-\frac{4}{x^2}dx$$