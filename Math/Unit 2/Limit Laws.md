# Example text
Given the function $f(x)=\frac{x^2-1}{x-1}$, what is happening to the output as x gets very close to 1?

## Limits
Let $f(x)$ be a function defined on the open interval $[a,b]$ around $c$ ($f(c)$ may pr may not exist.) The limit of $f(x)$ as $x$ approaches $c$ is the number $L$: $\lim\limits_{x\rightarrow c}f(x)=L$. $\lim\limits_{x\rightarrow c}f(x)=L$ if, for every number $\epsilon > 0$, there exists a corresponding number $\delta > 0$ such that for all $x$: $0<|x-c|<\delta=>f(x)-L|<\epsilon$

$0<|x-c|<\delta$
Measure of inputs within a range $f$

$|f(x)-L|<\epsilon$
Measure of how close our outputs are to some value $\epsilon$.

#### Example
Show $\lim\limits_{x\rightarrow1}(5x-3)=2$
$c=1$
$f(x)=5x-3$
$L=2$
$0<|x-1|<\delta=>f(x)-2|<\epsilon$

$|f(x)-1|<\epsilon$
$|5x-3-2|<\epsilon$
$|5x-5|<\epsilon$
$5|x-1|<\epsilon$
$|x-1|<\frac{\epsilon}{5}$
$0<|x-1|<\delta=|x*1|<\frac{\epsilon}{5}$
Since we now have both $\epsilon$ and $\delta$ in terms of $x-c$, we can say $\lim\limits_{x\rightarrow c}f(x)=2$.
#### Example
$f(x)=3-2x$, $c=3$, $\epsilon=.02$
$0<|x-c|<\delta=>|f(x)-L|<\epsilon$

$|3-2x-L|<.02$
$-.02<3-2x-L<.02$
$-3.02<-2x-L<-2.98$
$-3.02+2x<-L<-2.98+2x$
$-2x+3.02>L>-2x+2.98$

$0<|x-3|<\delta$

---
A way of getting arbitrarily close to a value without ever reaching that value. They let us see what the expected behavior at a point is.
$$\lim f(x)=1$$
$$x\rightarrow c$$
The limit as x approaches c (where c is some constant) of $f(x)$ is L (where L is some other constant)
$$\lim\limits_{x\rightarrow c}\frac{x^2-1}{x-1}=2$$
						Found Graphically. /\\
### Limit Laws
#### 1. Constant law
$\lim\limits_{x\rightarrow c}k=k$ where k is a constant
##### Example
$$\lim\limits_{x-5}3=3$$
#### 2. Identity
$\lim\limits_{x\rightarrow c}x=c$
##### Example
$$\lim\limits_{x\rightarrow5}x=5$$
$$Let \lim\limits_{x\rightarrow c}f(x)=L~\And~\lim\limits_{x\rightarrow c}g(x)=m$$
#### 3. Sum
$\lim\limits_{x\rightarrow c}(f(x)+g(x))=\lim\limits_{x\rightarrow c}f(x)+\lim\limits_{x\rightarrow c}g(x)$
#### 4. Difference
$\lim\limits_{x\rightarrow c}(f(x)-g(x))=\lim\limits_{x\rightarrow c}f(x)-\lim\limits_{x\rightarrow c}g(x)=L-M$
#### 5. Product
$\lim\limits_{x\rightarrow c}(f(x)*g(x))=\lim\limits_{x\rightarrow c}f(x)*\lim\limits_{x\rightarrow c}g(x)=L*M$
#### 6. Constant Multiple
$\lim\limits_{x\rightarrow c}(k*f(x))=K*\lim\limits_{x\rightarrow c}f(x)=K*L$
#### 7. Quotient
$\lim\limits_{x\rightarrow c}\frac{f(x)}{g(x)}=\frac{\lim\limits_{x\rightarrow c}f(x)}{\lim\limits_{x\rightarrow c}g(x)}=\frac{L}{M}$
#### 8. Power
$\lim\limits_{x\rightarrow c}(f(x))^n=(\lim\limits_{x\rightarrow c}f(x))^n=L^n$
#### 9. Root
$\lim\limits_{x\rightarrow c}(f(x))^{1/n}=(\lim\limits_{x\rightarrow c}f(x))^{1/n}=L^{1/n}$
#### 10. Polynomial
if $f(x)=a_nx^n+a_{n-1}x^{n-1}...+a_{n...}$
a sub some number is coefficient attached to each power of $y$
$\lim\limits_{x\rightarrow c}f(x)=f(c)$
#### 11. Rational Functions
If $f(x)$ and $g(x)$ are polynomial functions
$\lim\limits_{x\rightarrow c}\frac{f(x)}{g(x))}=\frac{f(c)}{g(c)}$ if $g(c)\neq 0$
#### 12. Squeeze/Sandwich Theorem
if $g(x)\leq f(x)\leq h(x)$
$\lim\limits_{x\rightarrow c}g(x)=\lim\limits_{x\rightarrow c}h(x)=L$
then the $\lim\limits_{x\rightarrow c}f(x)=L$
##### Example
$\lim\limits_{x\rightarrow2}(-x^2+5x-2)$
###### Sum Rule
$\lim\limits_{x\rightarrow2}(-x^2)+\lim\limits_{x\rightarrow2}(5x)+\lim\limits_{x\rightarrow2}(-2)$
$(-1)\lim\limits_{x\rightarrow2}(x^2)+(5)\lim\limits_{x\rightarrow2}(x)+(-1)\lim\limits_{x\rightarrow2}(2)$
$(-1)(\lim\limits_{x\rightarrow2}(x))^2+5(2)+(-1)$
$(-1)(2)^2+10-2$
$=-4+8$
$\lim\limits_{x\rightarrow2}(-x^2+5x-2)=4$
###### Polynomial
$\lim\limits_{x\rightarrow2}(-x^2+5x-2)=-(2)^2+5(2)-2$
$=4$
##### Example 2
$-x^2\leq f(x)\leq x^2$ find the $\lim\limits_{x\rightarrow0}f(x)$
$\lim\limits_{x\rightarrow0}(-x^2)\leq \lim\limits_{x\rightarrow0}f(x)\leq \lim\limits_{x\rightarrow0}(x^2)$
$0\leq \lim\limits_{x\rightarrow0}f(x)\leq 0$
$\lim\limits_{x\rightarrow0}f(x) = 0$

---
# Goal w/ delta-epsilon proofs:
Show that if $x$ is within $\delta$ of $c$, $f(x)$ is within $\epsilon$ of L.
#### Example
Show $\lim\limits_{x\rightarrow 4}(9-x)=5$
$$0<|x-c|<\delta => |f(x)-L|<\epsilon$$
$$0<|x-4|<\delta => |(9-x)-L|<\epsilon$$
$$|(9-x)-5|<\epsilon$$
$$|4-x|<\epsilon$$
$$|-(x-4)|<\epsilon$$
$$|x-4|<\epsilon$$
$$Let~\epsilon=\delta$$
$$0<|x-4|<\epsilon$$