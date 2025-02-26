![[Integration Example 0 Picture 1]]
# Rectangular approximation of the area under a curve
Given the continuous function $f(x)$ on the interval $[a,b]$, the area under $f(x)$ can be approximated by using $n$ rectangles:
$$A = \sum^{h}_{i=1} f(x_i^*)\Delta x$$
$$\Delta x=\frac{b-a}{n}$$
![[Integration Example 1 Picture 1]]
Area of the ith rectangle is $f(x_i)*\Delta x$
## The 3 most common approximations
- Upper Sum
	- Using left endpoints of rectangles![[Integration Example 0 picture 2]]
- Lower Sum
	- Using right endpoints of rectangles![[Integration Example 0 picture 3]]
- Midpoint sum
	- Use midpoints of rectangle![[Integration Example 0 picture 4]]
#### Example
Upper, Lower, and midpoint approximations for $f(x)=1-x^L$ using 4 rectangles(sub-intervals) on $[0,1]$
> $\Delta x=\frac{1-0}{4}=\frac{1}{4}$
> **Upper Approximation** ![[Integration Example 0 picture 5]]
> $f(x_1)=1-(0)^2=1$
> $f(x_2)=1-(\frac{1}{4})^2=\frac{15}{16}$
> $f(x_3)=1-(\frac{1}{2})^2=\frac{3}{4}$
> $f(x_4)=1-(\frac{3}{4})^2=\frac{7}{16}$
> $\sum^{4}_{i=1} f(x_i^*)*\Delta x=\Delta x\sum^{4}_{i=1} f(x_i^*)$
> $=\frac{1}{4}(1+\frac{15}{16}+\frac{3}{4}+\frac{7}{16})$
> $=\frac{25}{32}$ Upper
> **Lower Approximation**![[Integration Example 0 picture 6]]
> **Midpoint Approximation** ![[Integration Example 0 picture 7]]
> 