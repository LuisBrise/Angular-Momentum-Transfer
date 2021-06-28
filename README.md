# Angular-Momentum-Transfer
Programs to compute the angular momentum transfer from a STEM fast electron to a spherical nanoparticle

These routines are made on julia and are mean to work on a jupyter notebook (IJulia). For them to work correctly, you must add the following packages: 

*) SpecialFunctions, 
*) GSL,
*) FastGaussQuadrature and
*) Cuba.

To run, only make the last markdown cells executables (with Y)

At the beginning of each notebook, you can choose between three materials: Aluminum (Drude model), Gold (Werner) and Bismuth (Werner).

In the output-file cell you have to input the parameters for the angular momentum transfer calculation.

All routines need to use the dictionary l100-Ii1i2lm-julia-dictionary.jl
