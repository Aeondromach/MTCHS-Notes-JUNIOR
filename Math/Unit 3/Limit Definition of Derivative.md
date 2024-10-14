Slope at a point
$m=\frac{f(x+h)-f(x)}{h}$
# Limit Definition of the Derivative
$f^1(x)=\lim\limits_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$
"f prime of x"
1st derivative of $f(x)$

$f^1(x)$ is the slope (of tangent line) at all points on $f(x)$
#### Example
Find $f^1(x)$ when $f(x)=x^2$, then find the slope of the line tangent to $f(x)$ at $(1,1)$.
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{f(x+h)-f(x)}{h}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{(x+h)^2-x^2}{h}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{x^2+2xh+h^2-x^2}{h}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{2xh+h^2}{h}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{h(2x+h)}{h}$
	$f^1(x)=\lim\limits_{h\rightarrow0}2x+h$
	$f^1(x)=2x+0$
	$f^1(x)=2x$
##### Find the Slope of $f(x)$ at $(1,1)$.
	$f^1(1)=2(1)$
	$f^1(1)=2$
Slope at $(1,1)$ of $f(x)$ is $2$.
#### Example
Find $f^1(x)$ when $f(x)=\sqrt{x+2}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{\sqrt{(x+h)+2}-\sqrt(x)}{h}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{(\sqrt{x+h+2}-\sqrt{x+2})}{h}(\frac{\sqrt{x+h+2}+\sqrt{x+2}}{\sqrt{x+h+2}+\sqrt{x+2}})$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{((x+h+2)-(x+2)}{h(\sqrt{x+h+2}+\sqrt{x+2})}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{x+h+2-x-2}{h(\sqrt{x+h+2}+\sqrt{x+2})}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{h}{h(\sqrt{x+h+2}+\sqrt{x+2})}$
	$f^1(x)=\lim\limits_{h\rightarrow0}\frac{1}{\sqrt{x+h+2}+\sqrt{x+2}}$
	$f^1(x)=\frac{1}{\sqrt{x+0+2}+\sqrt{x+2}}$
	$f^1(x)=\frac{1}{2\sqrt{x+2}}$