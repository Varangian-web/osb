### Definition Highlights
#definitions

**Aerosol**: an assemblage of small particles, solid or liquid suspended in the air. The diameter from 100 microns down to 0.01 micro or less, e.g. dust, fog, smoke


**Air Filter**: An air cleaning device to remove light particulate loadings from normal atmospheric air before introduction into the building. Usual range: loadings upp to 3 gains per thousand cubic feet.

**Density Factor**: the ratio of actual air density to density of standard air. The product of the desnity factor and the density of standard air will give the actual air density in pounds per cubic foot,

$$ d \times 0.065 = actualDensity(\frac{lbs}{ft^3})
$$


Threshold Limit Value (TLV)  refers to the airborne concentrations of the substance and represents conditoins under which ti s believed that neraly all workers may be exposed day after day withnout adverse health effects


Time-weighted average (TWA) is defined as the time-weighted average concentrations for a conventional 8 -hour workday with 40 hours per week.

Exhaust system as categorized as local (LEV) or general


Dilution ventilation systems are normally used for contaminnt control only when local exhaust is impractical, as the large quantiites of temperedc replacement air required to offset the air exhaust can lead to high operating costs.

Local exhaust ventilations operate at capturing the contaminant at or near it's source. Local exhaust systems are comprised of four basic elements:


- the hood
- the duct system
- the air cleaning device
- the fan


Basic definition

The densitiy ($\rho$)  is defined as it's mass per unit at 14.7 psia and temperature of 70F
#formula #calculation #pressure #density


$$ p = \rho R T
$$

where:
p - the absolute pressure in pounds per squate foot 
$\rho$ - the density, lbm/ft^3
R - the gas constant for air and equals 53.35 ft-lb/lbm-degrees Rankine
T - the absolute temparature of the air in degrees Rankine

$R = F+459.7$

#condition #formula 

In dry air:

$$ \rho T = (\rho T )_{STD}
$$

$$\rho = \rho_{STD} \dfrac{T_{STD}}{T} = 0.075 \dfrac 530/T
$$


#formula #airflow 

cross-sectional airflow is 

$Q = V \cdot A$

#definitions 
Static pressure (SP ) is defined as the pressure in the duct that tendcs to burst or collapse expressed in " wg

Velocity presure(VP) is defined as teh pressure required to acceleate air from zero to velocity (V) $\in$ kinetic energecy of the air stresm

#formula #airflow #velocity
$$
V = 1096 \sqrt{\dfrac{VP}{\rho}}
$$

or 

$$VP = \rho (\dfrac{V}{1096})^2
$$

where:

V - velocity, fpm
VP - velocity pressure, "wg



#formula #totalpressure #pressure 

$TP = SP + VP$

TP can be positive or negative.



### Simplified assumptions #airflow #assumptions

Basic assumptions include:

1. Heat transfer effects are neglected. 
2. Compressibilit effects are neglected. If p<20"wg
3. The air assume to be dry. Water vapor would change density under high humidity.
4. The weight and volumen of the contaminant is ignored.



Note of conservation of energy:

$TP_1 = TP_2 + h_1$

$SP_1 + VP_1 = SP_2 + VP_2 + h_1$


where:
sub_1 - some upstream point
sub_2 - some downstream point
h_1 - all energy losses encountred by air during flow


###Acceleration of air and hood entry losses
[[Industrial Ventilation Manual.pdf#page=25]]

Solve for velocity from room to entry

$$ V = \dfrac{Q}{A}$$

identify pressure in "wg at STD


If no energy loss:

$SP_1 + VP_1 = SP_2 + VP_2$

therefore, 

$SP_2 = -VP_2$ , which is unrealistic
there must be losses

$SP_2 = -(VP_2 + h_d)$

Hood static suction ($SP_h$) :

$SP_h = - SP_2 = VP-2 + h_e

In summary, a static pressure downstream of the hood is negative due to two effects:

- Acceleration of air to the duct velocity; and
- Hood entry loses.


Alternative way to portray hood entry losses


$C_e = \sqrt{\dfrac{VP}{SP_h}}$

If there are no losses $SP_h=VP$ and $C_e=1.00$
However $C_e<1$ always

$C_e$ is a constant for any given hood and can be used to determine flow rate if $SP_h$ is known.
#airflow #hood #suction
$Q=V \cdot A = 1096A \sqrt{\dfrac{VP}{\rho}}= 1096 A C_e \sqrt{\dfrac{SP_h}{\rho}}$

#formula #STD #airflow 

$Q = 4005 A C_e \sqrt{SP_h}$


### Duct Losses #duct

[[Industrial Ventilation Manual.pdf#page=25i]]
#reynolds #losses #friction #duct 
$R_e = \dfrac{\rho dV}{\mu}$

where:

$\rho$ - density, lbm/ft^3
d - diameter, ft
v - velocity, ft/sec
$\mu$ - the air viscosity, lbm/s-ft

#surface #roughness
The effect on surface roughness is given by relative roughness, which is the ration of the absolute surface roughness (k), defined as the average height of the roughness elements on a particular type of material, to the duct diameter.


#moody_diagram

Moody combined these effects into a signle chart. [[Industrial Ventilation Manual.pdf]]

Reynolds number is the relative of the relative roughess and the friction coefficient.

#friction #losses #darcy_weisbach #formula
Darcy-Weisbach friction coefficient is used to determine the overall loses

$h_f = f \dfrac{L}{d}VP$

$h_f$ - friction losses in a duct, "wg
f - Moody diagram friction coefficient
L - duct length, ft
d - duct diameter, ft
VP - duct velocity pressure, "wg


Churchill solution in the entire range of laminar, critical and turbulent flows.

#formula #churchill #airflow 
ref : [[Industrial Ventilation Manual.pdf#page=26]]
$$f = 8 [ (\dfrac{8}{Re})^{12} + (A + B)^{-3/2}]^\dfrac{1}{12}$$

where :

$$A= {-2.457 ln[(\frac{7}{Re})^{0.9} + (\dfrac{k}{3.7D})]}^{16}$$

$$B = (\dfrac{37,530}{Re})^16$$

#formula #wright #simplificiation

$h_f = 2.74 \dfrac {(V/1000)^{1.9}}{D^{1.22}}$


where:

V - duct velocity, fpm
D - duct diameter, inches


output is "wg  er 100 feet of pipe under STD


#formula #loeffler #velocity #pressure #darcy_weisbach 

$h_f = (12 \dfrac{f}{D})L \cdot VP = H_f \cdot L \cdot VP$

12 - conversion factor in -> feet

$H_f = 12 \dfrac{f}{D} = \dfrac { aV^b }{Q^c}$

where "a" and exponents "b" and "c" vary as a function of duct material in 
Table 1-2   ref:  [[Industrial Ventilation Manual.pdf#page=27]] 

#### Fitting Losses

fitting losses are given by the loss coefficien (F) 

$h_{en} = F_{en} VP$




