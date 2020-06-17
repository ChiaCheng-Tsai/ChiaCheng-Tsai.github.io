---
layout: page
title: GetFem++
---
## GetFem++

GetFEM++ is an open source library based on collaborative development. 
It aims to offer a framework for solving potentially coupled systems of linear and nonlinear partial differential equations with the finite element method.
<img src="https://static.wixstatic.com/media/d19f46_81644996ae4841d78ffbae48ba140348.png/v1/fill/w_506,h_210,al_c,q_85,usm_0.66_1.00_0.01/d19f46_81644996ae4841d78ffbae48ba140348.webp" width ="350" height="250">

SuperLU is a general purpose library for the direct solution of large, sparse, nonsymmetric systems of linear equations on high performance machines.

<img src="https://static.wixstatic.com/media/d19f46_847d8141208d4572bd2125ae280a75ca.png/v1/fill/w_293,h_61,al_c,lg_1,q_85/d19f46_847d8141208d4572bd2125ae280a75ca.webp">

## Finite Element Method-Mild Slope Equation (FemMse)

- A generic FEM code (Tsai and Chou, 2015) is implemented for solving the MSE-type models of FemMse.
  Furthermore, quartic elements are adopted in the FEM numerical solution procedures.
  
- The present finite element model is generic. To be more clear, template parameters are implemented in the present model, such as the mild-slope equation type, bathymetry, dimensionality and others.
- We compare our result (CCMS) with the EMM (Tsai et al., 2011) and the IEM (Porter and Porter, 2000).

<img src="https://static.wixstatic.com/media/d19f46_c6e4037aafb44b309983a17db201bed7.png/v1/fill/w_576,h_403,al_c,q_85,usm_0.66_1.00_0.01/d19f46_c6e4037aafb44b309983a17db201bed7.webp" width ="350" height="250">

### Numerical Results

<img src="https://static.wixstatic.com/media/d19f46_6b7113353f814019b85a61b1c033d1b2.png/v1/fill/w_441,h_430,al_c,lg_1,q_85/d19f46_6b7113353f814019b85a61b1c033d1b2.webp" width ="350" height="250">

IEM solutions for the short-wave sinusoidal slope

<img src="https://static.wixstatic.com/media/d19f46_da3ec10a0d9349ff93af7785b74c52c9.png/v1/fill/w_650,h_299,al_c,lg_1,q_85/d19f46_da3ec10a0d9349ff93af7785b74c52c9.webp" width ="350" height="250">

Reflection coefficients for the sinusoidal shoal

<img src="https://static.wixstatic.com/media/d19f46_9e20f0f31ff342748805b666d939d546.png/v1/fill/w_724,h_363,al_c,q_85,usm_0.66_1.00_0.01/d19f46_9e20f0f31ff342748805b666d939d546.webp" width ="350" height="250">

### Reference

Chia-Cheng Tsai, and Wan-Rong Chou (2015) . Comparison between consistent coupled-mode system and eigenfunction matching method for solving water wave scattering. Journal of Marine Science and Technology, 23 , 870-881
Tsai, C.-C., Hsu, T.-W. & Lin, Y.-T. (2011) On step approximation for Roseau's analytical solution of water waves. Mathematical Problems in Engineering.
Porter, R. & Porter, D. (2000) Water wave scattering by a step of arbitrary profile. Journal of Fluid Mechanics, 411, 131-164.

[Back](https://finitetsai.github.io/research)
