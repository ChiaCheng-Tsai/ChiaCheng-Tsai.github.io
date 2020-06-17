---
layout: page
title: Method of Fundamental Solutions
---
## MFS for Laplace Equation

It is well known that the method of fundamental solutions (MFS) is a numerical method of exponential convergence. 
In other words, the logarithmic error is proportional to the node number of spatial discretization. 
In this study, the exponential convergence of MFS is demonstrated by solving Laplace equation in domains of rectangles, ellipses, amoeba-like shapes, and rectangular cuboids. 
In the solution procedure, the sources of the MFS are located as far as possible and the instability resulted from the ill-conditioning of system matrix is avoided by using the multiple precision floating-point reliable (MPFR) library. 
The results converge faster for the cases of smoother boundary conditions and larger area/perimeter ratios. The computation is scalable in the sense that the required time increases only algebraically. (Tsai and Lin, 2013)

<img src="https://static.wixstatic.com/media/d19f46_77c6d3f599144bdc85010238e8b20d23.png/v1/fill/w_650,h_450,al_c,q_85,usm_0.66_1.00_0.01/d19f46_77c6d3f599144bdc85010238e8b20d23.webp" width ="350" height="250"><img src="https://static.wixstatic.com/media/d19f46_a7addaa6db46462cbc6bb86b89c9773d.png/v1/fill/w_180,h_63,al_c,q_85,usm_0.66_1.00_0.01/d19f46_a7addaa6db46462cbc6bb86b89c9773d.webp">

<img src="https://static.wixstatic.com/media/d19f46_d41cdd8f956842218d05a1b3ae647de6.png/v1/fill/w_555,h_363,al_c,q_85,usm_0.66_1.00_0.01/d19f46_d41cdd8f956842218d05a1b3ae647de6.webp" width ="350" height="250"><img src="https://static.wixstatic.com/media/d19f46_f7edcea2169547e5a3d4f531869db5f7.png/v1/fill/w_536,h_366,al_c,q_85,usm_0.66_1.00_0.01/d19f46_f7edcea2169547e5a3d4f531869db5f7.webp" width ="350" height="250">
