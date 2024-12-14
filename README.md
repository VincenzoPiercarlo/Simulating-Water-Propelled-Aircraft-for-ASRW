## Simulating Water-Propelled-Aircraft for ASRW
This work takes place in the context of the [Airbus Sloshing Rocket Workshop 2023](https://sloshing.euroavia.eu/) and simulates the flight of a water-propelled model aircraft. The code lets the user manipulate the aircraft geometry to find the optimal geometry to maximize range and maximum altitude.


## Features
The work consists of a Simulink supported by several Matlab functions dealing with aerodynamics and inertial computations. Analyses are performed under the following hypothesis:
- The aircraft is a rigid body.
- There is zero sloshing.
- There is zero latency in avionics.
- Aircraft has longitudinal symmetry. 
The code imports the aircraft's aerodynamical properties from an external file, in the specific case extracted from low-fidelity analyses performed with Digital DATCOM +.


## Authors
- [Piercarlo Mirto](https://www.linkedin.com/in/piercarlo-mirto/)
- [Vincenzo Junior Di Rosa](https://www.linkedin.com/in/vincenzo-junior-di-rosa/)


## Acknowledgments
The authors were part of a team of six students from the Aerospace Engineering Bachelor's and Master's degree programs at the University of Naples Federico II. The team — the AirSloths — won the 2023 ASRW competition. If you are curious about the aircraft model proposed by the team, [here's a short video of our flight tests](https://www.youtube.com/watch?v=y8TNEQP7Qss).
