$\lim\limits_{x\rightarrow \infty}f(x)$
$\lim\limits_{x\rightarrow -\infty}f(x)$

# Limits at infinity of Rational Functions
---
## Find the highest degree polynomial in the numerator, and the denominator.
---
$f(x)=\frac{p(x)}{q(x)}$
Let $p$ be the degree of $p(x)$ and $q$ be the degree of $q(x)$
1. $p>q$, then $\lim\limits_{x\rightarrow \infty}f(x)$ is $\infty$
	Limit $\nexists$
2. $p<q$, then $\lim\limits_{x\rightarrow \infty}f(x)=0$
3. $p=q$, then $\lim\limits_{x\rightarrow \infty}f(x)=$ ratio of lending coefficients.
#### Example
$\lim\limits_{x\rightarrow \infty}\frac{1}{x}$
	$p(x)=1=x^0$
	$q(x)=x=x^1$
	$p=0$
	$q=1$
	$\lim\limits_{x\rightarrow \infty}\frac{1}{x}=0$
#### Example
$\lim\limits_{x\rightarrow \infty}\frac{5x^2+8x-3}{3x^2+2}$
	$p(x)=5x^2+8x-3$
	$q(x)=3x^2+2$
	$p=2$
	$q=2$
	$\lim\limits_{x\rightarrow \infty}\frac{5x^2+8x-3}{3x^2+2}=\frac{5}{3}$
## Horizontal asymptotes
---
$\lim\limits_{x\rightarrow \infty}f(x)=b$
$\lim\limits_{x\rightarrow -\infty}f(x)=b$
b is a constant.
#### Example
Find $\lim\limits_{x\rightarrow \infty}\sin(\frac{1}{x})$
	$\lim\limits_{x\rightarrow \infty}\frac{1}{x}=0$
	$\lim\limits_{x\rightarrow \infty}\sin(0)=0$
#### Example
$\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}$
	$\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}+\lim\limits_{x\rightarrow \infty}2$
	$\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}+2$
	$0\leq |\frac{\sin(x)}{x}|\leq|\frac{1}{x}$ or $\frac{-1}{x}\leq\frac{\sin(x)}{x}\leq\frac{1}{x}$
	$\lim\limits_{x\rightarrow \infty}0\leq\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}\leq\lim\limits_{x\rightarrow \infty}\frac{1}{x}$
	$0\leq\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}\leq0$
	$\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}=0$
	$\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}+2=\lim\limits_{x\rightarrow \infty}\frac{\sin(x)}{x}+\lim\limits_{x\rightarrow \infty}2$
	$=0+2$
	$=2$
#### Example
$\lim\limits_{x\rightarrow \infty}x-\sqrt{x^2+16}$
	$\lim\limits_{x\rightarrow \infty}x-\sqrt{x^2+16}$