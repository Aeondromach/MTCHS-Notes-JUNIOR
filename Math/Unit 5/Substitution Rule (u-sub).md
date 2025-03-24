If $u=g(x)$ is differentiable and $f$ is continuous, then:
$$\int f(g(x))g^1(x)dx=\int f(u)du$$
# Indefinite Integral
Unbounded integral
$$\int f(x)dx=F(x)+c \leftarrow\text{constant}$$
#### Example
$\int (x^3+x)^5(3x^2+1)dx$
> Let $v=x^3+x$
> $du=3x^2+1dx$
> $\int u^5du$
> $=\frac{u^6}{6}+c$
> $=\frac{(x^3+x)^6}{6}+c$
#### Example
$\int \sqrt{2x+1}~dx$
> Let $u=2x+1$
> $du=zdx$
> $\frac{1}{2}du=dx$
> $\int \sqrt{u}(\frac{1}{2})du$
> $\frac{1}{2}\int u^\frac{1}{2} du =$
> $\frac{1}{2}(\frac{2}{3}u^\frac{3}{2})+c=$
> $\frac{1}{3}u^\frac{3}{2}+c=$
> $\frac{1}{3}(2x+1)^\frac{3}{2}+c$
#### Example
$\int x\sqrt{2x+1}~dx$
> Let $u=2x+1 \rightarrow \frac{u-1}{2}=x$
> $du=2dx$
> $\frac{1}{2}du=dx$
> $\int x\sqrt{u}(\frac{1}{2})du$
> $\int \frac{1}{2}(u-1)\sqrt{u}(\frac{1}{2})du$
> $\frac{1}{4}\int(u-1)\sqrt{u}du=$