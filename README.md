# Sensorless Sliding Mode Observer for PMSM using Sigmoid Switching Function
Simulink simulation of a sensorless sliding mode observer for surface magnet brushless motor.
Requires the Simulink Motor Control Toolbox. 
Note: This simulation is not built on the SMO Observer included in the Motor Control Toolbox. It is built from discrete blocks in Simulink.
This leaves the user free to experiment with the SMO loop and to implement other variations of SMO. 
There is a super twisting algorithm switching function block in the SMO, although I have not read much on the theory and it only partially works. 
Increasing the sigmoid exponent variable sigmoid_a will make the function more like a signum. 
Simply run the motor parameter script to initialize variables and run the Simulink simulation. 



