Slope of a line between 2 points

---
## Secant
(x,y) and (2x,2y) are points
The slope of the line that these points lie on is:
$m=\frac{y_2-y_1}{x_2-x_1}=\frac{\delta y}{\delta x}=\frac{f(x_2)-f(x_1)}{x_2-x_1}$

Slope between two points is known as the average rate of change "RoC" on that interval.
#### Example
Find the avg RoC of $f(x)=x^?$ on $[1,3]$
$$m=\frac{f(3)-f(1)}{3-1}=\frac{3^2-1^2}{2}=\frac{9-1}{2}=\frac{8}{2}$$
$$m=4$$
Finding the slope of lines tangent to a curve
	(Instantaneous rate of change)

---
## Tangent
$m=\frac{\delta y}{\delta x}=\frac{f(x_2)-f(x_1)}{x_2-x_1}=\frac{f(x_2+h)-f(x_1)}{h}$
$h = x_2-x_1$
$(x_2,f(x_2))=(x_1+h,f(x_1+h))$
#### Example
Find the Instantaneous RoC (slope) of $f(x)=x^2$ when $x=3$
$$m=\frac{f(x_1+h)-f(x_1)}{h}$$
$$m=\frac{(x_1+h)^2-x_1^2}{h}$$
$$m=\frac{x_1^2+2x_1h+h-x_1^2}{h}$$
$$m=\frac{2x_1h+h^2}{h}$$
$$m=\frac{h(2x_1+h)}{h}$$
$$m=2x_1+h$$
$$let~h=0$$
$$m=2x_1$$
$$x_1=3$$
$$m=2*3$$
$$m=6$$
Inst. RoC of $f(x)=x^2$ at $x=3$ is $6$.
#### Example 2
$$f(x)=x^2-2x-3~~~P(2,-3)$$
$$m=\frac{f(x+h)-f(x)}{h}$$
$$m=\frac{((x+h)^2-2(x+h)-3)-(x^2-2x-3)}{h}$$
$$m=\frac{x^2+2xh+h^2-2x-2h-3-x^2+2x+3}{h}$$
$$m=\frac{2xh+h^2-2h}{h}$$
$$m=\frac{h(2x+h-2)}{h}$$
$$m=2x+h-2$$
$$m=2x-2$$
$$m=2(2)-2$$
$$m=2$$
##### Point Slope
$$y-(-3)=2(x-2)$$$$y+3=2x-4$$
$$y=2x-7$$