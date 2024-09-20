ethanmensior@gmail.com
Sigma@1984
# #Function

Takes an Input of $(x)$ and produce 1 output of $f(x)$.

X => [Function] => $f(x)$

---
# #Real_Numbers

All numbers (-∞, ∞)

---
# #E

Is an element

---
# #Vertical_Line_Test

Given the graph of something, if a vertical line can be drawn at every point on that graph without intercepting more than one point, that graph is representing a [[A-Definitions#Function|function]].

---
# #Families_Of_Functions

## #Linear

A graph going in a straight line.
$$y=mx+b$$
### Domain

All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
### Range

All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$

---

## #Exponential

A graph that exponentially increases.
$$y=a*b^x+c$$
### Domain
All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
### Range
All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$
Must be >0.
### More
$e = 2.718$

---

## #Polynomials

$$x^n+x^n~^-~^1+x^n~^-~^2$$
Sin, Cos, Tan, Sec, Csc, Cot.
### #Quadratic

A graph turning into a U shape.
$$y=x^2$$
#### Domain

All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
#### Range

All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$
Must be >=0.

---

### #Cubic

A graph turning into a sideways S shape.
$$y=x^3$$
#### Domain

All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
#### Range

All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$

---

## #Rational_Graph

$$f(x)=P(x)/Q(x)$$
#### Domain

All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
#### Range

All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$

---
## #Logarithms

$$Log(x)$$
#### Domain

All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
#### Range

All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$

---

## #Root_Functions

### #Square_Root_Functions 

$$\sqrt{x}$$
#### Domain

All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
#### Range

All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$

---

## #Reciprocal_Functions

$$f(x)=1/x$$

goes into two opposite L shapes.
### Domain
All real numbers of X
X [[A-Definitions#E|E]] $\mathbb{R}$
X =/= 0
### Range
All real numbers of Y
Y [[A-Definitions#E|E]] $\mathbb{R}$
X =/= 0

# #Even_And_Odd_Functions

## #Even_Functions

Any [[A-Definitions#Function|f(x)]] where $$f(-x)=f(x)$$
In general when $x^n$ where $n$ is even the $x^n$ is an even [[A-Definitions#Function|function]].

## #Odd_Functions

Any [[A-Definitions#Function|function]] [[A-Definitions#Function|f(x)]] where $$f(-x)=-f(x)$$

---
$$f(x) = x^3$$
$$f(-x)=f(-x)^3$$
$$f(-x)=(-x)(-x)(-x)$$
$$f(-x)=(x^2)(-x)$$
$$f(-x)=-x^3$$

---
In general, when x^n is a [[A-Definitions#Function|function]] and n is odd, the f(x) is an odd [[A-Definitions#Function|function]].

---

## #Composite_Functions

When we have 2 [[A-Definitions#Function|functions]] $f(x)$ and $g(x)$ where the output of one [[A-Definitions#Function|function]] is the input of the other [[A-Definitions#Function|function]].
$f(g(x))$
"$f$ of $f$ of $x$"

#### Example:
	$f(x)=x+1$
	$g(x)=x^2$
	-------------
	$f(g(x))=(x^2)+1$
		Replace $x$ with g(x) | $x => x^2$
		
	$g(f(x))=(x+1)^2$
		Replace $x$ with f(x) | $x^2 => (x+1)^2$
#### Example 2:
	$f(x)=\sqrt{x}$
	$g(x)=x+1$
	$h(x)=x^3$
		$f(g(h(x)))=$
			$g(h(x))=(x^3)+1$
			$f(x(x^3+1)) = \sqrt{(x^3)+1)}$
### Domain
If the domain of $f(x)$ is $A$ and the domain of $g(x)$ is $B$, where $A$ and $B$ are sets of numbers, then the domain of $f(g(x))$ is $A \cap B$
#### Example:
	$f(x)=x^2$
	$g(x)=\sqrt{x}$
What is the domain of f(g(x))?
	Domain $x^2$: $\mathbb{R}$
	Domain $\sqrt{x}$: $x >= 0$
	Domain of $f(g(x))$ is $x >= 0$
### Range
Given $f(x)$ and $g(x)$, the range of $f(g(x))$ is the range of $f(x)$ that lies within the range of $g(x)$ Let the range of $f(x) = A$, Let the range of $g(x) = B$.
$A \bigcap B$

## #Compound_Functions

Performing [[A-Definitions#Standard_Operation|standard operations]] on multiple [[A-Definitions#Function|functions]].
#### Example:
	$f(x)=x^2$
	$g(x)=x^3$
	-----
	$f(x)+g(x)=x^2+x^3$
	$f(x)+g(x)=x^2-x^3$
	$g(x)-f(x)=x^3-x^2$
	$f(x)*g(x)=x^2*x^3=x^5$
	$\frac{f(x)}{g(x)}=\frac{x^2}{x^3}=x^-1$
	$\frac{g(x)}{f(x)}=\frac{x^3}{x^2}=x$
### Domain and Range
#### Addition & Subtraction
For $f(x)+g(x)$ and $f(x)-g(x)$ where $A$ is the domain of $f(x)$ and B is the domain of $g(x)$, the domain is $A \bigcap B$ 
#### Division
For $\frac{f(x)}{g(x)}$ the domain is $A \bigcap B$, where $g(x)\neq0$

# #Symmetries

## [[A-Definitions#Even_Functions|Even Functions]]

Y axis mirrors.

# [[A-Definitions#Odd_Functions|Odd Function]]

Origin symmetry.

# #Standard_Operation

$$+, -, *, \div$$

# #Transformations

## #Vertical_Shifts

$f(x)+k$
#### Example:
$x^2+2$
Parabola shifted up 2 units.

## #Horizontal_Shifts

$f(x+h)$
$h>0$ left shift
$h<0$ right shift
#### Example:
$(x+1)^2$ Left shifted Parabola

## #Reflections

$-f(x)$ $x$ axis reflection
#### Example:
$-(x^2)$ Parabola opening down

$f(-x)$ $y$ axis reflection
#### Example:
$(-x)^3$ cubic reflected across y axis

## #Scaling

### #Vertical_Stretch

$C*f(x)$ |1 $2*x^2$

### #Vertical_Compression

$\frac{1}{C}*f(x)$ | $\frac{1}{2}x^2$

### #Horizontal_Stretch

$f(\frac{1}{C}*x)$ | $(\frac{x}{2})^2$

### #Horizontal_Compression

$f(C*x)$ | $(2x)^2$

## #Trig_Transformations

General form of sine and cosine
$f(x)=Asin(\frac{2\pi}{B}(x-c))+D$
$f(x)=Acos(\frac{2\pi}{B}(x-c))+D$
$A,B,C,D$ are all constants
$|A| =$ amplitude
$|B|=$ period
$C=$ Horizontal shift
$D=$ Vertical shift
#### Example:
$cos(2x)-1$
$A=1$
$B=\pi$
$C=0$
$D=-1$

---

## #Amplitude

Distance from the midline of a [[A-Definitions#Function|function]].
Midline = $3$ height = $6$, Amplitude = $6$.

## #Period

How long a [[A-Definitions#Function|function]] takes to repeat itself.

{ $Rwl$ } { $Rwl$ } { $Rwl$ }

# #Trig_Identities

$cos(\theta)=x$
$sin(\theta)=y$
radius of unit circles is 1.

## #Pythagorean_Identities

$sin^2(\theta)+cos^2(\theta)=1$
$1+tan^2(\theta)=sec^2(\theta)$
$1+cot^2(\theta)=csc^2(\theta)$
$sec(\theta)=\frac{1}{cos(\theta)}$
$csc(\theta)=\frac{1}{sin(\theta)}$
$cot(\theta)=\frac{1}{tan(\theta)}$

## #Additive_Identities

$cos(A+B)=cos(A)cos(B)-sin(A)sin(B)$
$sin(A+B)=sin(A)cos(B)+cos(A)sin(B)$
Where A and B are variables, angles, etc.

## #Double_Angle_Formulas

$cos(2\theta)=cos^2(\theta)-sin^2(\theta)$
$sin(2\theta)=2sin(\theta)cos(\theta)$

## #Half_Angle_Formulas

$cos^2(\theta)=\frac{1+cos(2\theta)}{2}$
$sin^2(\theta)=\frac{1-cos(2\theta)}{2}$

## #Even_And_Odd_Trig

$sin(-\theta)=-sin(\theta)$
$cos(-\theta)=cos(\theta)$
$tan(-\theta)=-tan(\theta)$
$cot(-\theta)=-cot(\theta)$
$csc(-\theta)=-csc(\theta)$
$sec(-\theta)=sec(\theta)$

## #Reciprocal_Identities

$cot(\theta)=\frac{1}{tan(\theta)}$
$csc(\theta)=\frac{1}{sin(\theta)}$
$sec(\theta)=\frac{1}{cos(\theta)}$

## #Quotient_Identities

$tan(\theta)=\frac{sin(\theta)}{cos(\theta)}$
$cot(\theta)=\frac{cos(\theta)}{sin(\theta)}$

## #Trig_Verifications

A way of showing/proving that one trigonometry expression is equivalent to another trigonometry expression.

#### Example:
Verify that $tan(\theta)cos(\theta)=sin(\theta)$
	$tan(\theta)=\frac{sin(\theta)}{cos(\theta)}$
$\frac{sin(\theta)}{cos(\theta)}*cos(\theta)=sin(\theta)$
$sin(\theta)=sin(\theta)$

