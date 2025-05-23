The solid generates by rotating a region about an axis in this plane.
# Volume for Disks for rotations about the x-axis
![[Solids of Revolution Example 0 Picture 1]]
![[Solids of revolution example 0 picture 2]]
![[Solids of revolution example 0 picture 3]]
$A(x)=\pi(R(x))^2$
$V=\int^b_x(\pi(R(x))^2)dx$
#### Example
Find the volume of the solid generated by rotating the region between the curve $y=\sqrt{x}$, $0\leq x\leq4$, and the x-axis about the line $y=0$
> ![[Solids of revolution example 1 picture 1]]
> $$V=\int^4_0\pi(\sqrt{x})^2dx$$$$V=\int^4_0\pi x dx$$$$V=\frac{\pi x^2}{2}|^4_0=8\pi$$
#### Example
Find the volume of the solid generated by revolving the region bounded by $y=\sqrt{x}$ and the lines $y=1$, $x=4$ about the line $y=1$.
> ![[Solids of Revolution Example 2 Picture 1]]
> $R(x)=\sqrt{x}-1$
> $V=\int^4_1\pi(\sqrt{\pi}-1)^2dx$
> $V=\int^4_1\pi(x-2\sqrt{x}+1)dx$
> $V=\pi[\frac{x^2}{2}-\frac{4}{3}x^{\frac{3}{2}}+x|^4_1]$
> $V=\pi[(\frac{16}{2}-\frac{4}{3}(\sqrt{64})+4)-(\frac{1}{2}-\frac{4}{3}+1)]$
> $V=\pi(\frac{16}{2}-\frac{32}{3}+4-\frac{1}{2}+\frac{4}{3}-1)$
> $V=\frac{7\pi}{6}$
# Volumes of Disks rotated about the y-axis
$V=\int^d_c \pi[R(y)]^2dy$
![[Solids of Revolution Example 0 Picture 4]]
#### Example
Find the volume of the solid generated by revolving the region between the parabola $x=y^2+1$ and the line $x=3$ about the line $x=3$.
> ![[Solids of Revolution Example 3 Picture 1]]
> $R(y)=3-(y^2+1)=2-y^2$
> $y^2+1=3$
> $y^2=2$
> $y=\pm\sqrt{2}$
> $V=\int^{\sqrt{2}}_{-\sqrt{2}}\pi(2-y^2)^2dy$
> $V=\int^{\sqrt{2}}_{-\sqrt{2}}\pi(4-2y^2+y^4)dy$
> $V=2\pi\int^{\sqrt{2}}_{0}4-2y^2+y^4dy$