# Volume of a solid
The volume of a solid of an integrable cross section area $A(x)$ from $x=a$ to $x=b$:
$$\int^b_aA(x)dx$$
![[Disks and Washers Example 0 Picture 1.excalidraw]]
# Calculating the volume of a solid
1. Sketch the solid and a cross section.
2. Find the formula of a typical cross section. $A(x)$
3. Find bounds of integration
4. Integrate $A(x)$ to find volume.
#### Example
A pyramid $3m$ high has a square base that is $3m$ on a side. the cross section of the pyramid perpendicular to the altitude $xm$ down from the vertex is a square $xm$ on a side. Find the volume of the pyramid.
> ![[Disks and Washers Example 1 Picture 1.excalidraw]]
> $$V=\int^3_0x^2dx$$$$V=\frac{x^3}{3}|^3_0=\frac{3^3}{3}-\frac{0^3}{3}=9m^3$$
#### Example
A curved wedge is cut from a cylinder of radius 3 by two planes. One plane is perpendicular to the axis of the cylinder. The second plane crosses the first plane at $45\degree$ angle to the center of the cylinder. Find the volume of the wedge.
> ![[Disks and Washers Example 2 Picture 1.excalidraw]]
> Eq. of Circle: $x^2+y^2=r^2$
> $x^2+y^2=3^2$
> $y=~^\pm\sqrt{9-x^2}$
> $A(x)=x*2\sqrt{9-x^2}$
> $A(x)=2x\sqrt{9-x^2}$
> $V=\int^3_0 2x\sqrt{9-x^2}dx$
> $let u=9-x^2$
> $du=-2xdx$
> $v=-\int^0_9\sqrt{u}du$
> $v=\int^9_0 u^{\frac{1}{2}}du=18$