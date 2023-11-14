Rocket Sim
==========

This is a simulation of the control of a rocket with 6 degrees of freedom.
The purpose of this was for me to challenge myself with programming the control algorithm. Therefore, everything else is quite barebones.

How to Run
----------
1. Download the release to the right.
2. Extract the .zip file.
3. Run RocketSim.exe.

How to Control the Rocket
-------------------------
- Set the target X, Y, Z co-ordinates (and roll angle in degrees) using the input fields in the top left corner. Press [Enter] to send them to the rocket.
- Press [Space] to swap between the main camera and an onboard camera.
- Press [Escape] to exit the simulation.

How the Rocket Controls Itself
------------------------------
The rocket can only control its position and orientation using the main engine and two small RCS thrusters as described below:
- The main engine can throttle from 0-100%, and gimbal in two axes to a maximum of +/- 10 degrees.
- The two RCS thrusters are used only for roll control


There are many limits programmed in to make the rocket slightly more "realistic". For example, gimbal rate limits, roll rate limits, horizantal velocity limits, etc.
