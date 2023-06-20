# Data-Analysis-Using-HPC-Codes-TARANG-For-Magenetohydodynamics
Numerical simulation are often used to test the prediction of MHD turbulence here We are simulating the data
using ’TARANG’ which having following features:
1. Pseudo-spectral python code
2. Object oriented design.
3. General PDE solver for Fluid, MHD, Convection etc.
Here for time advance we use Time advance (e.g., Euler’s scheme). To compute the nonlinear term (pseudo-
spectral) first we convert the data which is in Fourierspace to real using IFFT then multiple with the another
component of same field to generate the nonlinear term which is quadratic in nature. Work flow of the code works
as follows:
[code_work_flow ](https://github.com/Gopesh998/Data-Analysis-Using-HPC-Codes-TARANG-for-Magenetohydrodynamics/assets/137176367/e2b9cd4f-e45e-4cc7-84a3-1aeae73d5858)


