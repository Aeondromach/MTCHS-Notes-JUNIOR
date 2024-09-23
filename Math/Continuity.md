If a function is continuous on an interval $[a,b]$, then it is a single, unbroken line.

# Continuity Test
*For continuity at a point*
Given a function $f(x)$ and the point $x=c$, for $f(x)$ to be continuous at $c$:
1. $\lim\limits_{x\rightarrow c}f(x)$ must exist.
2. $f(c)$ must exist ($c$ must be in the domain of $f(x)$)
3. $f(c)=\lim\limits_{x\rightarrow c}f(x)$
#### Example
Determine if $f(x)=\frac{(x+2)(x*2)}{(x-2)}$
Continuous at $x=1$ and $x=2$

$x=1$
$$\lim\limits_{x\rightarrow 1}\frac{(x+2)(x*2)}{(x-2)}=\frac{3(-1)}{-1}=3=f(1)$$
$f(x)$ when $x=1$ is continuous.

---
$x=2$
$$\lim\limits_{x\rightarrow 2}\frac{(x+2)(x*2)}{(x-2)}=\lim\limits_{x\rightarrow 2}x+2=4$$
$f(2)$ is undefined because $2$ is not in the domain of $f(x)$

$\lim\limits_{x\rightarrow 2}f(x)\neq f(2)$, $f(x)$ is not cont. at $x=2$.

# For Continuity on $[a,b]$
1. $f(x)$ must be continuous for all $c$. $a<c<b$
2. $\lim\limits_{x\rightarrow a^+}f(x)=f(a)$
3. $\lim\limits_{x\rightarrow b^-}f(x)=f(b)$
# Types of Discontinuities
1. Hole (Removable Discontinuities)
	- $f(x)$ has a piece missing, can use a piecewise function to fix it.
2. Jump Discontinuity (None Removable)
	- jumps in value
3. infinite (asymptote) (Non Removable)
	- goes to opposite infinities, so cannot be filled in.