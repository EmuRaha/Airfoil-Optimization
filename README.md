Shape optimization of NACA0012 using ANN based surrogate model. 
The “Hicks-Henne bump function” has been used to parameterise and deform the original shape according to design parameters. 
Sampling parameters are generated using quasi-random low-discrepancy sequences called “Sobol” sequences. 
Numerical simulations have been conducted using the potential flow-based panel method solver “XFOIL” to obtain lift and drag coefficients of deformed foil shapes. 
An ANN-based surrogate model has been trained to predict the lift-coefficient and drag-coefficient corresponding to design parameters. 
The Python library “scipy. optimise” has been used to optimise the surrogate model to obtain optimal design parameters. 
The objective is to maximise aerodynamic efficiency, and the constraints were set to keep the drag coefficient less than the original airfoil and area constant.
