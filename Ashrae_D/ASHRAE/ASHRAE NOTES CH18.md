# Nonresidential cooling and heating load calculations 
## Intro
---
Heating and cooling load calculations are the primary design basis for most heating and air-conditioning 

External components: Walls, roofs, windows, skylights, doors, partitions, ceilings, and floors

Internal components:Lights, people, appliances, and equipment

Infiltration: Air leakage and moisture migration

System: Outdoor air, duct leakage and heat gain, reheat, fan and pump energy, and energy recovery 

## Internal Heat Gains 
---

#### People [[ASHRAE NOTES CH9]]

#### Lighting:
#equations
$$ 
q_{el} =3.14WF_{ul}{F_sa}
$$

The total light wattage is obtained from the ratings of all lamps installed, both for general illumination and for display use 

The lighting use factor is the ratio of wattage in use, typically the factor is one 

The special allowance factor is the ratio of light fixtures to power consumption

![[Pasted image 20210721111008.png]]	

#### Electric motors
 
 heat gain from equipment operated by electric motors in a conditioned space is calculated from:
 #equations 
 #conditions 
 
 $$
 q_{em} = 2545(P/E_M)F_{UM}F_{LM}
 $$
 ![[Pasted image 20210721112015.png]]
 
 $$
 q_{em} = 2545P(\frac{1.0-E_M}{E_M})F_{UM}F_{LM}
 $$
 
 ## Infiltration and moisture migration heat gains 
 
 ### Infiltration 
 
 Sensible heat loss, equivalent to the sensible heating load from infiltration:
 
 $$
 q_s = 60(cfm/ \nu) c_p(t_{in}-t_o)
 $$
 ![[Pasted image 20210721135123.png]]
 
 ## Ventilation 
 ### mixed Air Systems 
 
 For systems that mix hot and cold airstreams, the contribution to the heat transport system load is:
 $$
 \frac Q_h Q_c = (T_c -T_r)/(T_r-T_h)
 $$
 
 ### Duct Leakage 
 #important 
 
 Air leakage from supply ducts can considerably affect HVAC energy use. It reduces cooling and /or dehumidifying capacity for the space, and is offset by the increasing of airflow withing the system.
 
 ## Mathematical description 
 
 ### Conduction Process 
 
 GO BACK TO PG 424 Heat balance equations equations 25 and 26 are #important 