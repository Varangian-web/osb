[[ASHRAE - Objective 1]]

# Mass Transfer 

## Intro 
---
Mass transfer by convection or molecular diffusion occurs through the mixture and relative motion of a concentration gradient. In air conditioning, water vapor is added or removed from the air by simultaneous transfer of heat and mass(water vapor) between the airstream and a wetted surface.

The notes below will address mass transfer principles and provide methods of solving a simultaneous heat and mass transfer problem. This can be applied to analyzing the performance of cooling coils, evaportive condensers, cooling towers and air washers.

### Understanding Fick's Law 
---
#Law 
#equations 
$$
J_B = -\rho D_v \frac {d(\rho_B/\rho)}{dy}=-J_A
$$
$$
J_B = -C D_v \frac {d(C_B/C)}{dy}=-J_A
$$
where 
$$
\rho = \rho_A + \rho_B
$$
$$
C = C_A + C_B
$$

### Diffusion Coefficient

---

#definition 
Molecular Diffusion: The primary mechanics of mass diffusion at ordinary temperature and pressure conditions

A simplified intermolecular potential field function of water vapor and air can be used such as the equation below.
#equations 
$$
D_v = \frac {1.46x10^-4}{p}(\frac{T^{2.5}}{T + 441})
$$

![[Pasted image 20210716092225.png]]

Within non-polar gases, the inter-molecular forces are independent of the relative orientation of molecules, depending only on the separation distance form each other. 

Lastly there is structure-sensitive diffusion. 
#equations 


## Convection of Mass 
----

Here is the the usual stuff:

- [ ] dffvd


- hell
- hi
- here
- [x] adsf


Most external convective mass transfer problems can be solved with an appropriate formulation that relates the mass transfer flux to the concentration difference across the boundary layer 
#equations 
Convective mass transfer coefficient 
$$ 
{h_M} \underline = \frac {mdot_B " }{\rho_{Bi}-\rho_{Bb}}
$$

![[Pasted image 20210716093541.png]]
This case mass flow rate is defined as the mass flux of a gas(B) from a surface 

#important 
Heater transfer to water from air supplies the energy required to evaporate the water 

$$
q=hA(T)
$$

You can use the Nusselt, Prandlt, Reynolds and Staton numbers to calculate the various laminar and turbulent flow conditions to calculate the local mass transfer coefficient 

#equations 