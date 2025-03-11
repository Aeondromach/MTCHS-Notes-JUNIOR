1. Part 1:
	If $f(x)$ is continuous on $[a,b]$, then $F(x)=\int^{x}_{a}f(t)dt$ is continuous on $[a,b]$ and differentiable on $(a,b)$. The derivative is $f(x)$
		$$F^1(x)=\frac{d}{dx}\int^{x}_{a}f(t)dt=f(x)$$
#### Example
Find $\frac{dy}{dx}$ if $y=\int^{x}_{a}(t^3+1)dt$
> $$\frac{dy}{dx}=\frac{d}{dx}\int^{x}_{a}t^3+1dt$$
> $$\frac{dy}{dx}=x^3+1$$
2. Part 2:
	If $f$ is continuous over $[a,b]$ and $F$ is any anti-derivative (integral) of $f$ on $[a,b]$, the: $$\int^{b}_{a}f(x)=F(b)-F(a)$$