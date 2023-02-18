# Spacecraft-Dynamics-Mars-Mission

This repository contains code for the final project of "Spacecraft Dynamics" by prof. Hanspeter Schaub. The aim is to develop a Mars mission ADCS simulation. The simulator includes: 
* Three mission modes (sun-pointing, nadir-pointing/science, communication)
* Orbital motion simulator
* Coordinate frame transformations (from 3 mission frames to body frame and inertial orbit frame)
* Attitude error evaluator (in terms of Modified Rodrigues' Parameters)
* RK4 integrator to simulate state dynamics
* Controller with PD law implemented, having constants tuned according to given specifications. It is responsible for driving the angular velocity to zero and aligning the body frame to the reference frame
