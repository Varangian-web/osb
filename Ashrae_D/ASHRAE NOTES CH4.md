[[ASHRAE - Objective 1]]

# Heat Transfer 
-----

Remember that conduction, convection and radiation are the modes of heat transfer that moves energy from a higher to lower temperature region

Conduction example
#equations 
$$
q\propto{\frac{(t_s1-t_s2)A_c}L} 
$$
$$
q = k {\frac{(t_s1-t_s2)A_c} L } = {\frac {(t_s1-t_s2) } {L/(kA_c)} }
$$

![[Pasted image 20210715075205.png]]
#example 

Convection Example 
#equations 

$$
q =  {h_cA_s(t_s-t_\infty)} = {\frac {(t_s-t_\infty) } {1/(h_cA_s)} } 
$$
#example 
![[Pasted image 20210715094344.png]]

### Black Body
---------------
Understand that this is a surface or body that absorbs all radiation 

## Combined Radiation and Convection 
-------
When the temperature at the surface is equal to T_infinity, the total heat transfer from a surface by convection and radiation combined is the following 
#equations 
$$
q = q_{rad} + q_{conv}= (t_s-t_\infty){A_s}(h_r+h_c)
$$

## Overall Resistance and Heat Transfer Coefficient
-----
Understanding that thermal on electrical resistance can be calculated in the same manner is essential. A solid, fluid or gas medium can be though of as electrical resistivity. This means that your resistivity can be calculated by the following 
#equations 
$$ 
R_1 = {\frac {1}{hA}}
$$
$$
R_2 = {\frac {L}{kA}}
$$
$$
R_2 = {\frac {(1/h_cA)(1/h_rA)}{(1/h_cA)+(1/h_rA)}}
$$
$$
q = {\frac { (t_{f1} - t_{f2} ) }{R_1+R_2+R_3...} }
$$
$$
{\frac { (t_{f1} - t_{f2} )} q} = {\frac {1}{UA}} = {R_1+R_2+R_3}
$$

## Two and Three Dimensional Steady State Conduction: Shape Factors 
------
For calculating the various cases that include conduction as a mode of heat transfer. The rate is expressed as the following equation 
#equations 

$$
q = Sk(t_{1} - t_{2})
$$

The following cases can be substituted for the S factor of the condition 

PG#67

![[ASHRAE_handbook_fundamental.pdf]]


## Extended Surfaces 
-----

Extended surfaces such as heat fins may can be used within the calculation of the hvac/ahu system but it might be overkill to go that route. Depending on what or how the shape of the fin is, the heat transfer varies. It may not be present.

## Other unmentioned sections 
----

Most of the unmentioned sections will ultimately not be used. Things such as fluid flow along a plate or within a duct or various channels does not pertain to the task at hand. 