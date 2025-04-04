![[Area between Curves Example 0 Picture 1]]
If $f$ and $g$ are continuous with $f(x)\geq g(x)$ on $[a,b]$, then the area A between the curves $y=f(x)$ and $y=g(x)$ is $$A=\int^{b}_{a}(f(x)-g(x))~dx$$
#### Example
Find the area of the region bounded by $y=2e^{-x}+x$ and $y=\frac{e^x}{2}$ bounded by $x=0$ and $x=1$
> $$2e^{-x}+x=\frac{e^x}{2}\leftarrow\text{Check Intersection}$$
> $$\frac{2}{e^x}+x-\frac{e^x}{2}=0$$
> ![[Area between curve Example 1 Picture 1]]
> $$A=\int^{1}_{0}(2e^{-x}+x)-(\frac{e^x}{2})~dx$$
> $$A=-2e^{-x}+\frac{x^2}{2}-\frac{e^x}{2}|^1_0$$
> $$A=(-2e^{-1}+\frac{1}{2}-\frac{e}{2})-(-2+0-\frac{1}{2})$$
> $$A=3-\frac{2}{e}-\frac{e}{2}$$
> $$A=0.9051$$
#### Example
Find the area enclosed by $y=2-x^2$ and $y=-x$
> $$2-x^2=-x$$
> $$2-x^2+x=0$$$$-x^2+x+2=0$$$$(x+1)(x-2)=0$$
> Bounds $[-1,2]$ $$f(x)=2-x^2$$$$g(x)=-x$$$$f(0)=2-(0)^2=2$$$$g(0)=-(0)=0$$$$A=\int^{2}_{-1}(2-x^2)-(-x)~dx$$$$A=\int^{2}_{-1}2+x-x^2~dx$$$$A=2x+\frac{x^2}{2}-\frac{x^3}{3}|^2_{-1}$$
> $$A=\frac{9}{2}$$