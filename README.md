# TandemWIngStateSpaceModel

State Space model of a Tandem wing UAV for cruise flight condition. MATLAB file format ".mat"

Matlab File ".mat" contains state space matrices (A, B, C & D)

No. of Inputs: 4 (Aileron, Elevator, Rudder & Throttle commands) in the same order

No. of States: 10 (U, V, W, P, Q, R, Phi, Theta, Psi, Altitude) in the same order

No. of Outputs: 10 (All the states are made available at output)

'D' is a zero matrix


See attached figures for design dimensions and visual appearance of the tandem wing UAV.


The force and moment coefficients for different angle of attack, side slip and control surface deflections are obtained using the XFLR5 analysis software. Using the Newton-Euler 6-DoF equations of motion (EoM), the dynamic model of the UAV is developed by feeding the force and moment coefficients as a look-up table. Damping moment coefficients were also obtained from XFLR5 and the same is also used in the dynamic model. State space model of the UAV is obtained from the dynamic model using the MATLAB linear analysis tool. 
