If $g^1$ is continuous on $[a,b]$ and $f$ is continuous on the range of $g(x)=u$, then:
$$\int^{b}_{a}f(g(x))g^1(x)dx=\int^{g(b)}_{g(a)}f(u)du$$
#### Example
Evaluate $\int^{1}_{-1}3x^2\sqrt{x^3+1}dx$
	Plug the original bound $[a,b]$ into the $u$ equation to adjust to the new bounds $[g(a),g(b)]$, as shown below:
> Let $u=x^3+1=g(x)$              $g(-1)=(-1)^3+1=0$
> $du=3x^2dx$                              $g(1)=(1)^3+1=2$
> $\int^{2}_{0}\sqrt{u}du$
##### Methods to solve
1. $$\int^{2}_{0}u^{\frac{1}{2}}du$$$$\frac{2u^{\frac{3}{2}}}{3}|^{2}_{0}=$$$$\frac{2}{3}(2^{\frac{3}{2}})-\frac{2}{3}(0^{\frac{3}{2}})=$$$$\frac{2}{3}\sqrt{2^3}=$$$$\frac{2}{3}*2\sqrt{2}=$$$$=\frac{4\sqrt{2}}{3}$$
2. $$\frac{2}{3}u^{\frac{3}{2}}|^{2}_{0}=$$$$\frac{2}{3}(x^3+1)^{\frac{3}{2}}|^{1}_{-1}=$$$$\frac{2}{3}((1)^3)+1)^{\frac{3}{2}}-\frac{2}{3}((-1)^3+1)^{\frac{3}{2}}=$$$$\frac{2}{3}(2)^{\frac{3}{2}}-\frac{2}{3}(0)^{\frac{3}{2}}=$$$$\frac{2}{3}(\sqrt{8})=$$$$\frac{2}{3}2\sqrt{$$