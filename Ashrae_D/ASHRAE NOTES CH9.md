[[ASHRAE - Objective 1]]
# Thermal Comfort 
-----
## Intro
Thee main reason for HVAC system is to provide thermal comfort conditions for humans. This section summarizes the fundamentals of human thermoregulation and comfort in terms for the operating systems and designing the comfort/health of the occupants within the buildings 

The mind of the occupant reaches their own conclusion about thermal comfort and discomfort from:

- direct temperature from the skin 
- moisture sensations from the skin 
- deep body temperatures 
- efforts to regulate body temperatures 


A resting adult produces about 350 Btu/h of heat.
For a resting person this is about (50 kcal/h·m^2 ) or 1 met through their skin

### Energy Balance of the body 
----

The total metabolic rate M within the body is the metabolic rate required for the person's activity in addition to the 

#equations 
$$ 
M - W = q_{sk}+q_{res}+S
$$
or 
$$
M-W =(C+R+E_{sk})+(C_{res}+E_{res})+(S_{sk}+S_{cr})
$$

![[Pasted image 20210717072304.png]]

Heat dissipates from the body o the immediate surroundings by several modes of heat such as:

- latent heat flow from sweat evaporation 
- evaporation of moisture diffused through the skin 
- sensible heat flow during respiration 
- latent heat flow from evaporation of moisture from respiration

For a common clothed person make sure to account for the three modes of heat transfer, but if there is no direct contact with surfaces, you only need to account for convection and radiation of the skin.

![[Pasted image 20210717070453.png]]

#equations 
$$
S_{cr}=\frac{(1-\alpha_{sk})mc_{p,b}}{A_D}\times \frac {dt_{cr}}{d\theta}
$$
$$
S_{sk}=\frac{\alpha_{sk}mc_{p,b}}{A_D}\times \frac {dt_{sk}}{d\theta}
$$
![[Pasted image 20210717074152.png]]

The fraction skin mass depends on the rate of blood flowing to the skin surface.

### Thermal Exchanges with Environment 
----

Sensible heat exchange from the skin must pass through the persons clothing and 
#equations 
$$
C= f_{cl}h_c(t_{cl}-t_a)
$$
$$
R= f_{cl}h_r(t_{cl}-t_r)
$$
![[Pasted image 20210717075218.png]]

$$
C+R=f_{cl}h(t_{cl}-t_o)
$$
Where: 
$$
t_o = \frac {h_r t_r+h_c t_a}{h_r+h_c}
$$
$$
h = h_r+h_c
$$

To fully calculate the convective and radiative heat exchange from the skin that passes through the clothing to the environment, use the following equation:
#equations 
$$
C+R =\frac {(t_{sk}-t_o)}{R_{cl}+1/(f_{cl}h)}
$$

 The following table lists the typical metabolic rates for average adults. 
 
![[Pasted image 20210717080054.png]]


### Garment Insulation Values 
-----
This section is too detailed with the various items of clothing that will be present for each person working. Probably won't be extremely useful



### Environmental Parameters 
-----

#important 
Seven pyschrometric parameters used to describe the thermal environment are 
1. air temperature
2. wet-bulb temperature
3. dew-point temperature
4. water vapor pressure
5. total atmospheric pressure 
6. relative humidity 
7. humidity ratio

[Here](https://www.engineeringtoolbox.com/psychrometric-chart-d_816.html)  is a #chart for a pyschrometric reading when using a wet and dry bulb.


ASHRAE Thermal sensation scale:

- +3 = hot 
- +2 = warm
- +1 = slightly warm 
- 0 neutral
- -1 slightly cool 
- -2 cool
- -3 cold

Generally an approximate 6F or 0.44 change in water vapor pressure is necessary to change a thermal sensation by one unit 

![[Pasted image 20210717081524.png]]

In general with humidity levels, it is okay to be on the low-humidity end, while if a worker approaches a high humidity, the skin moisture tends to lead to discomfort. This is due to the increased friction between skin and clothing. To prevent discomfort, ensure realitve humidity does not exceed 60%. It is also important to note that many of the processes that are preformed such as paint cannot be performed in a high humidity environment.


Keeping the range of temperature within the optimum values also bodes better for the organization as well as the individual

![[Pasted image 20210717084425.png]]

It is clear that by moving away from the optimum temperature, it decreases the performance of the workers.

### Wind Chill Index 
-----
The index describes the rate of heat loss from the cylinder by radiation and convection for a  speed of the wind 


![Wind Chill Chart](https://www.weather.gov/images/safety/windchill21.gif)

### Environmental Conditions 
----
![[Pasted image 20210717090417.png]]