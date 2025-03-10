---
aliases:
  - Rolle's Theorem
---
If $f(x)$ is continuous over the closed interval $[a,b]$ and differentiable at every point on the interior $(a,b)$, then if $f(a)=f(b)$ $\exists$ at least one number $c$ in $(a,b)$ such that $f^1(c)=0$.
![[Mean Value Theorem Example 0 Picture 1]]
## Mean Value Thm. (MVT)
Suppose $f(x)$ id contininuous on$[a,b]$ and differentiable on $(a,b)$. Then there is at least one point $c$ in $(a,b)$ where:
$$f^1(c)=\frac{f(b)-f(a)}{b-a}$$
![[Mean Value Theorem Example 0 Picture 2]]
#### Example
Find the value(s) $c$ such that $\frac{f(b)-f(a)}{b-1}=f^1(c)$ on $[0,3]$ for $f(x)=3x^2$.
	$f^1(c)=\frac{3(3)^2-3(0)^2}{3-0}$
	$f^1(c)=\frac{27}{3}=9$
	$f(x)=3x^2$ -> $f^1(x)=6x$
	$f^1(c)=6c=9$
	$6c=9$
	$c=\frac{9}{6}$
	$c=\frac{3}{2}$
## Mean Value
$$\bar{x}=\frac{1}{b-a}\int^{b}_{a}f(x)dx$$
$\bar{x}$ = mean
#### Example
Given $f(x)=3x+2, find the average value on $[1,3]\rightarrow[a,b]$
> $$\bar{x}=\frac{1}{3-1}\int^{3}_{1}3x+2dx$$
> $$=\frac{1}{2}(\int^{3}_{1}3xdx+\int^{3}_{1}2dx)$$
> $$=\frac{1}{2}(3\int^{3}_{1}xdx+\int^{3}_{1}2dx$$
> $$\frac{1}{2}(3(\frac{3^2}{2}-\frac{1^2}{2})+2(3-1))$$
> $$=\frac{1}{2}(3(\frac{9}{2}-\frac{1}{2})+4)$$
> $$=\frac{1}{2}(3(4)+4)$$
> $$=8$$