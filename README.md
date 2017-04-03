# Calculation of doping-induced mechanical nonlinearity in silicon-based MEMS

Written by Kirill Moskovtsev, Michigan State University, 2016.
moskovts --at-- msu.edu

## About
This is the code for calculating nonlinearity induced by electron-phonon coupling in silicon microelectromechanical systems (MEMS). The code 
also calculates the temperature dependence of frequency for these devices. The theory used in this code and results produced by the code
are published in:

Kirill Moskovtsev, and M. I. Dykman. “Strong vibration nonlinearity in semiconductor-based nanomechanical
systems.” Phys. Rev. B 95, 085426 (2017) ([download](https://arxiv.org/abs/1611.09912 from arXiv))


There are two pieces of code here. The code in *c_ijm_through_F_public.ipynb* 
calculates analytical expressions for elastic constants of Si and Ge and saves them to 'single_expressions' folder.

*mode_calculation.ipynb* takes these expressions and calculates nonlinear frequency shift for 
Lame and Extension mode for a square plate and a thin beam respectively.

The code is written in Python 2.7 and packaged in Jupyter Notebook files. You need Jupyter Notebook installed
to open them. You can view the notebooks converted to HTML in the 'html' folder.



The software is publicly available under the MIT open-source license.