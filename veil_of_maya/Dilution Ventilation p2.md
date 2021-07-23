### Worker Protection


extends: [[Dilution Ventilation And Control]]
link: [[Heat Loss Prevention Program notes]]

- In generally good physical conditon and not obese, are heat acclimatized, and are experienced inteh heat stressing job. They also need to know how to select clothing and maintain whol body hydration and electrolyte leves to provide th greatest comfort and safety.
- In areas that are well-ventilated and shileded from infraraed radiant heat sources.
- Knowledgeable about the effects of their medications on cardivascular and peripheral vascular function, blood pressure control,  body temperature maintennace, sweat gland activity, metabolic effects and elvels of attention and conciousness
- Appropriately supervised where there is a history of alcohol use
- Provided accurante verbal and written instruction, frequent training progarm and other information about heat stress and strain.


General Ventilation Provisions

To determine the requied general ventilation, the designer must estimate the acceptable temperature and humidity rise. The first step in determined the required volumetruc flow  is to the sensible and latent heat load. Next, determine the volumetric flow to dissipate the sensible heat and the volumetric flow to disspoate the latent heat. The reuqired general ventilation is the large of the two volumetric flows.

The sensible heat rise is determined

$H_s = Q_s \times \rho \times c_p \times \Delta T \times (60 min/hr)$


where:
$H_s$ - sensible heat gain, BTU/hr
$Q_s$ - Volumetric flow for sensible heat, cfm
$\rho$ - Density of the air, $lbm/ft^3$
$c_p$ - Specific heat of the air, $BTU/lbm-F$
$\Delta T$ - change in temperature, F

default:
$c_p$ = 0.24 $BTU /lbm - F$
$\rho$ = 0.065 $lbm/ft^3$

simplification to the heat equation
$H_s = 1.08 \times Q_s \times \Delta T$
or 
$Q_s = \dfrac{H_s} {(1.98 x \Delta T)}$


Latent heat load:

$$H_1 = Q_1 \times \rho \times c_1 \times \Delta h \times (60 min/hr)\times (1lb/7000 grains)$$

where:

$H_1$ - latent gear gain, btu\hr
$Q_1$ - volumentric flow for latent heat, cfm
$\rho$ - density of the air, $lbm/ft^3$
$\Delta h$ - change in absolute humidity of teh air, grains-water/lbm-dry air

$c_1$ = 970 BTY/lb and $\rho$ = 0.075 $lbm/ft^3$

Simplfiication => 
$H_1 =0.62 \times Q_1 \times \delta h$

or 
$Q_1 = \dfrac {H_1} {0.62 \times \Delta h}$

Rate of moisture released is know then:

$$M = Q_1 \times \rho \times \Delta h \times (1lb / 7000 grains) \times (60 min/hr) = Q_1 \times \rho \times \Delta h \div (116.7)$$

$$Q_1 = \dfrac {116.7 \times M}{\rho \times \Delta h}$$


Many designes consider that air temperature on supply should not exceed 80 F
Reference figure 2-8 and 2-9 for effectient cross flow control of excess heat.


