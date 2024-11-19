# Linearization
Used to find a linear approximation of $f$ at $x=a$.
$L(x)=f(a)+f^1(a)(x-a)$
![[Linearization main Picture 1.excalidraw]]
#### Examples
##### Find the linearization of $f(x)=\sqrt{1+x}$ at $x=1$
$L(x)=f(a)+f^1(a)(x-a)$

$a=1$
$f(a)=f(1)=\sqrt{1+1}=\sqrt{2}$
$f^1(x)=\frac{1}{2\sqrt{x+1}}$
$f^1(a)=f^1(1)=\frac{1}{2\sqrt{1+1}}=\frac{1}{2\sqrt{2}}$
$L(x)=\sqrt{2}+\frac{1}{2\sqrt{2}}(x-1)$
$L(1.1)=\sqrt{2}+\frac{1}{2\sqrt{2}}(1.1-1)$
$=\sqrt{2}+\frac{.1}{2\sqrt{2}}$
$=1.4496$
$f(1.1)=1.4491$
# Differential
$dx$ & $dy$ are both differentials.
$y=f(x)$
$\frac{d}{dx}(y)=\frac{d}{dx}(f(x))$
$\frac{dy}{dx}=f^1(x)$
$dy=f^1(x)dx$
#### Examples
##### Find $dy$ when $y=x^5+37x$
$dy=f^1(x)d(x)$
$f(x)=x^5+37x$
$f^1(x)=5x^4+37$
$dy=(5x^4+37)dx$
##### Find $dy$ when $y=x^5+37x$ with $x=1$ and $dx=.2$
$dy=(5x^4+37)dx$
$dy=(5(1)^4+37)(.2)$
$dy=8.4$