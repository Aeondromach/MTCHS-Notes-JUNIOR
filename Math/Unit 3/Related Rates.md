# Solving Related Rate Problems
1. Draw a diagram. Label variables and constants.
2. write out given information.
3. Write down what you are trying to solve for.
4. Find an equation(s) that relate all variables
5. Take the derivative with respect to time.
6. Evaluate.
#### Examples
##### Water is filling a conical tank at a rate of 9ft$^3/$min. The tank is inverted such that the base is towards the sky with a height of 10ft and a base radius of 5ft. How fast is the water rising when the water is 6ft deep?
![[Related Rates Example 1 Draw 1]]
$\frac{dv}{dt}=9\text{ft}^3/\text{min}$
$y=6ft$
$V=\frac{1}{3}\pi x^2y$
![[Related Rates Example 1 Draw 2]]
$\frac{5}{10}=\frac{x}{y}$
$\frac{y}{2}=x$
$V=\frac{1}{3}\pi(\frac{y}{2})^2y$
$V=\frac{\pi}{3}*\frac{y^3}{4}$
$V=\frac{\pi y^3}{12}$
$\frac{d}{dt}(V)=\frac{d}{dt}(\frac{\pi y^3}{12})$
$\frac{dV}{dT}=\frac{\pi}{12}*3y^2*\frac{dy}{dt}$
$\frac{dV}{dt}=\frac{\pi}{4}y^2*\frac{dy}{dt}$
$\frac{\frac{dV}{dt}}{\frac{\pi y^2}{4}}=\frac{dy}{dt}$
$\frac{9}{\frac{\pi (6)^2}{4}}=\frac{dy}{dt}$
$\frac{9}{\frac{36\pi}{4}}=\frac{dy}{dt}$
$\frac{9}{9\pi}=\frac{dy}{dt}$
$\frac{1}{\pi}=\frac{dy}{dt}$
# Tip, look for triangles