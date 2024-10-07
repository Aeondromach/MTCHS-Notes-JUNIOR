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
#### Example (how to want to kill yourself)
$\lim\limits_{x\rightarrow \infty}x-\sqrt{x^2+16}$
	$\lim\limits_{x\rightarrow \infty}x-\sqrt{x^2+16}(\frac{x+\sqrt{x^2+16}}{x+\sqrt{x^2+16}}$
	$\lim\limits_{x\rightarrow \infty}\frac{x^2-(x^2+16)}{x+\sqrt{x^2+16}}$
	$\lim\limits_{x\rightarrow \infty}\frac{-16}{x+\sqrt{x^2+16}}$
	$\lim\limits_{x\rightarrow \infty}\frac{\frac{-16}{x}}{\frac{1}{x}(x+\sqrt{x^2+16})}$
	$\lim\limits_{x\rightarrow \infty}\frac{\frac{-16}{x}}{1+\frac{1}{x}\sqrt{x^2+16}}$
	$\lim\limits_{x\rightarrow \infty}\frac{\frac{-16}{x}}{1+\sqrt{\frac{x^2}{x^2}+\frac{16}{x^2}}}$
	$\lim\limits_{x\rightarrow \infty}\frac{\frac{-16}{x}}{1+\sqrt{1+\frac{16}{x^2}}}$
	$=\frac{\lim\limits_{x\rightarrow \infty}\frac{-16}{x}}{\lim\limits_{x\rightarrow \infty}1+\sqrt{1+\frac{16}{x^2}}}$
	$=\frac{0}{\lim\limits_{x\rightarrow \infty}1+\sqrt{1+\frac{16}{x^2}}}$
	$\lim\limits_{x\rightarrow \infty}\frac{16}{x^2}=0$
	$=\frac{0}{\lim\limits_{x\rightarrow \infty}1+\sqrt{1+0}}$
	$=\frac{0}{\lim\limits_{x\rightarrow \infty}2}$
	$=\frac{0}{2}=0$
## Vertical Asymptotes
---
The line $x=a$ (a is a constant) is a vertical asymptote if $\lim\limits_{x\rightarrow a^+}f(x)=+/-\infty$ or $\lim\limits_{x\rightarrow a^-}f(x)=+/-\infty$.
#### Example
Find the vertical asymptotes of $f(x)=\frac{1}{x+2}$
	$\lim\limits_{x\rightarrow -2^+}\frac{1}{x+2}=-\infty$
	$\frac{1}{-2+2}=\frac{1}{0}=0$
	$\frac{1}{-2.01+2}=\frac{1}{-.01}=-100$
	$\lim\limits_{x\rightarrow -2^+}\frac{1}{x+2}=\infty$
	Vertical asymptote at x=-2.
#### Example
Find the Horizontal asymptote and vertical asymptote of $f(x)=\frac{x+3}{x+2}$
	Horz:
	$\lim\limits_{x\rightarrow \infty}\frac{x+3}{x+2}=1$
	Horizontal asymptote at $y=1$
	---
	Vert:
	$\lim\limits_{x\rightarrow -2^-}\frac{x+3}{x+2}=-\infty$
	$\lim\limits_{x\rightarrow -2^-}\frac{x+3}{x+2}=\infty$
	Vertical asymptote at $x=2$
	