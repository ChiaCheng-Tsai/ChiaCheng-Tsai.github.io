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

## MFS for Helmholtz Eigensolution
In this study, the exponential convergence of the MFS is demonstrated by obtaining the eigensolutions of Helmholtz equation. In the solution procedure, the sought solution is approximated by a superposition of the Helmholtz fundamental solutions and a system matrix is resulted after imposing the boundary condition. A golden section determinant search method is applied to the matrix for finding exponentially convergent eigenfrequencies. In addition, the least-square method of fundamental solutions is applied for solving the corresponding eigenfunctions. (Tsai and Young, 2013)

<img src="https://static.wixstatic.com/media/d19f46_c74aef5368f74dc8ad95a2c0dda18575.png/v1/fill/w_636,h_425,al_c,q_85,usm_0.66_1.00_0.01/d19f46_c74aef5368f74dc8ad95a2c0dda18575.webp" width ="350" height="250"><img src="https://static.wixstatic.com/media/d19f46_2cf5463c74a2428ab10c97bca610651f.png/v1/fill/w_450,h_50,al_c,q_85,usm_0.66_1.00_0.01/d19f46_2cf5463c74a2428ab10c97bca610651f.webp">

<img src="https://static.wixstatic.com/media/d19f46_cda39f65bfd648c6a6e632f452065ae3.png/v1/fill/w_500,h_161,al_c,q_85,usm_0.66_1.00_0.01/d19f46_cda39f65bfd648c6a6e632f452065ae3.webp"><img src="https://static.wixstatic.com/media/d19f46_cde872aec7504b1abb21818217ef7273.png/v1/fill/w_605,h_335,al_c,q_85,usm_0.66_1.00_0.01/d19f46_cde872aec7504b1abb21818217ef7273.webp" width ="350" height="250">

<img src="https://static.wixstatic.com/media/d19f46_a490acea6bea4d75ba3d10f050ecd7ea.png/v1/fill/w_516,h_300,al_c,q_85,usm_0.66_1.00_0.01/d19f46_a490acea6bea4d75ba3d10f050ecd7ea.webp" width ="350" height="250"><img src="https://static.wixstatic.com/media/d19f46_bef2842575cd417496fceae66516ab92.png/v1/fill/w_755,h_550,al_c,q_90,usm_0.66_1.00_0.01/d19f46_bef2842575cd417496fceae66516ab92.webp" width ="350" height="250">


[Back](https://finitetsai.github.io/research)
