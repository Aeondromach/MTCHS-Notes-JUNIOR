# L'Hôpital's rule
"La pee-tall"
If $f(a)=g(a)=0$, and $f$ and $g$ are differentiable on the open interval $I$ containing $a$, and where $g(x)\neq 0$, then:
$$\lim\limits_{x\rightarrow a}\frac{f(x)}{g(x)}=\lim\limits_{x\rightarrow a}\frac{f^1(x)}{g^1(x)}$$
#### Example
Evaluate $\lim\limits_{x\rightarrow 0}\frac{3x-\sin{x}}{x}$
> $\lim\limits_{x\rightarrow 0}\frac{3x-\sin{x}}{x}=\frac{0}{0}$
> $\lim\limits_{x\rightarrow 0}\frac{3x-\sin{x}}{x}=\lim\limits_{x\rightarrow 0}\frac{3-\cos{x}}{1}=2$
## L'Hôpital's for $\frac{\infty}{\infty}$
$\lim\limits_{x\rightarrow a}\frac{f(x)}{g(x)}=\lim\limits_{x\rightarrow a^\pm}\frac{f^1(x)}{g^1(x)}$
#### Example
$\lim\limits_{x\rightarrow \frac{\pi}{2}}\frac{\sec{x}}{1+\tan{x}}=\frac{\infty}{\infty}$
> $\lim\limits_{x\rightarrow \frac{\pi}{2}}\frac{\sec{x}\tan{x}}{\sec^2{x}}=\lim\limits_{x\rightarrow \frac{\pi}{2}^-}\frac{\tan{x}}{\sec{x}}=\sin{x}=\sin{\frac{\pi}{2}}=1$
> $\lim\limits_{x\rightarrow \frac{\pi}{2}}\frac{\sec{x}}{\tan{x}}=1$
#### Example
$\lim\limits_{x\rightarrow \infty}\frac{\frac{1}{x}}{\frac{1}{\sqrt{x}}=\lim\limits_{x\rightarrow \infty}\frac{\sqrt{x}}{x}$