# LumpedMassSpring_Umbilical_model
Matlab code for an LMS umbilical model, with spherical bound nodes for linkage of segments. Using fourth-order Runge-Kutta and secant method for finding solution numerically.

# MATLAB file contains

- Detailed comments for explanation
- Detailed explanation of the equation of motion for each node
- Use and navigation of 3 dimensional matrices in MATLAB
- Secant method for prediction step
- Fourth-order Runge-Kutta method
- Plots for visualization of umbilical dynamics


Examples of plots:

![image](https://user-images.githubusercontent.com/26135452/202168341-4872b846-8056-4602-b6c4-c066293d3d85.png)
![image](https://user-images.githubusercontent.com/26135452/202170003-2be6580e-9ce2-477d-9f08-cf0872665199.png)

# To use the model:

step 1: Give umbilical parameters.
- Umbilical weight, given in weight per km of umbilical cable.
- Umbilical cable length
- Umbilical cable diameter
- Young's modulus (if using tension for boundary conditions)
- Tangential and normal drag coefficients (Can be estimated through the use of Reynolds number)

step 2: Give model parameters.
- Timestep
- Umbilical nodes/segments
- Simulation runtime

% work in progress
