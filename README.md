This source code package includes the MATLAB source codes for the Cauchy proximal splitting algorithm.

These Matlab functions implement a proximal splitting method involving a non-convex penalty function based on the heavy-tailed Cauchy distribution. A function for calculating the proximal operator of the Cauchy prior is provided, and two examples are included to illustrate how to perform cost function optimisation with a forward-backward (FB) -based algorithm that implements the corresponding Cauchy proximal splitting (CPS) method. The two signal processing examples include 1D signal denoising in the frequency domain and image de-blurring.

This package includes three MATLAB scripts:

	1) CauchyProx		: The MATLAB function that performs the proximal operator operation for the Cauchy penalty function.
				  
	2) CPS_1D_denoising	: An example code for 1D signal denoising via the Cauchy proximal splitting algorithm.
				  
	3) CPS_2D_deblurring	: An example code for 2D image deblurring via the Cauchy proximal splitting algorithm.
				  		
*****************************************************************************************************************
LICENSE

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

Copyright (C) Oktay Karakus <o.karakus@bristol.ac.uk> 
		and 
	      Alin Achim <alin.achim@bristol.ac.uk>, 
	      12-05-2020, University of Bristol, UK
	      
*****************************************************************************************************************
REFERENCE

[1] O Karakus, P Mayo, and A Achim. "Convergence Guarantees for Non-Convex Optimisation with Cauchy-Based Penalties"
       IEEE Transactions on Signal Processing 68 (2020): 6159-6170.

https://arxiv.org/abs/2003.04798

[2] O Karakus, A Achim. (2020): Cauchy Proximal Splitting (CPS). 
	
https://doi.org/10.5523/bris.15y437loa26cr2nx8gnn3l4hzi
	
*****************************************************************************************************************

