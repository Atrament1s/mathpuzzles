---
title: High School Question 3 Solution
---
>$$ \\ $$
>Determine the circulation of the vector field $\overset{\rightharpoonup}{F}(x,y,z)=\langle 3x+y,2x-z,y+2z\rangle$ about the surface defined by $x^{2}+y^{2}+z^{2}=9,z\geq 0$.
>$$ \\ $$

$$ \\ $$
Since the edge of the surface is a closed curve, evaluate using Stokes' Theorem. The boundary curve of the surface is $\overset{\rightharpoonup}{r}(t)=\langle 3\cos t, 3\sin t, 0\rangle$ for $0\leq t\leq 2\pi$.

$$
\overset{\rightharpoonup}{F}\cdot d\overset{\rightharpoonup}{r}=\langle 9\cos t+3\sin t,6\cos t,3\sin t\rangle\cdot\langle-3\sin t,3\cos t,0\rangle
$$

$$
=-27\sin t\cos t-9\sin ^{2}t+18\cos ^{2}t
$$

$$
=-27\sin t\cos t+9\sin ^{2}t-18\sin ^{2}t+18\cos ^{2}t
$$

$$
=-\frac{27}{2}\sin 2t+18\cos 2t+\frac{9}{2}(1-\cos2t)
$$

$$
=\frac{9}{2}-\frac{27}{2}\sin 2t+\frac{27}{2}\cos 2t
$$

Using Stokes' Theorem:

$$
\iint_{S}\overset{\rightharpoonup}{F}\cdot d\overset{\rightharpoonup}{\sigma}=\int ^{2\pi}_{0}\left( \frac{9}{2}-\frac{27}{2}\sin 2t +\frac{27}{2} \cos 2t \right)  \, dt 
$$

$$
=\left( \frac{9}{2}t+\frac{27}{4}\cos 2t+\frac{27}{4} \sin 2t \right)\Bigg\vert^{2\pi}_{0} 
$$

$$
=\left( 9\pi +\frac{27}{4}\right)-\left( \frac{27}{4} \right)=9\pi 
$$
