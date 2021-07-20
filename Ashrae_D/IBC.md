#ASHRAE 
[[ASHRAE NOTES CH13]]
#conditions 

Inlet Boundary Conditions may include 

- velocity 
- pressure
- mass flow 

When details of flow distribution are unknown, a constant-pressure boundary or constant flow rate can be specified. 

The pressure inlet boundary requires specifying static pressure for incompressible flow. 

Mass flow rates and temperature are defined at the boundary, while velocities and pressure are calculated by extrapolation at inlet boundaries 

#equations 

Air supply velocity for the momentum source is calculated from the mass flow rate and the diffuser effective area 
$$
U_0 = \frac{\dot{m}}{\rho A_0}

$$
![[Pasted image 20210720085254.png]]
Using the prescribed velocity method has been used in numerical prediction of room air movement. The Inlet profiles are given as boundary conditions of a simplified slot diffuser. For the #model of diffusers in large spaces #reference
![[rv2002-1.pdf]]


