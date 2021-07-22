# Ventilation and infiltration
## Intro 
---
Ventilation air is used to proved acceptable indoor air quality.

The air handler unit can supply air that is recirculated or from the outside environment.  The air formed can be mixed when supplied by either being forced or bypassed when windy or thermal conditions present themselves. 

Outside air fraction is the ratio of volumetric flow rate of outside air brought in by the air handler to the total supply airflow rate:

The Air exchange rate "I" compares airflow to volume 
#equations 
$$
I = \frac Q V
$$

Q = volumetric flow rate of air into space, cfm
V = interior volume of space 

## Averaging Time-Varying Ventilation
#important 
The concept of effective ventilation describes the proper ventilation rate averaging process. The constant source strengths pollutants relationship
#equations 
$$
I_m =  \frac {\overline Q} V = \frac F {V \overline C} = \frac 1 {\overline \tau_e}
$$

where 

I_m = effective air exchange rate
Q_bar = average volumetric flow rate of air into space, cfm
V = interior volume of space 
F= Contaminant source strength 
C_bar = concentration 
tau_bar = time-averaged effective turnover time 

The time averaged turnover can be caterogized as 

$$
\overline \tau_e = \frac 1 N \sum^N_{i=1} \tau_{e,i}
$$

![[Pasted image 20210721130945.png]]

### Age of air
#equations 

When time-dependent data of tracer gas concentration are available, the age of air can be calculated from 

$$
\theta_{age} = \int^{\infty}_{\theta = 0} \frac {C_{in}-C} {C_{in}-C_o} d\theta
$$

Ventilation effectiveness is a description of an air distribution system's ability to remove internally generated pollutants from a building.

$$
V (\frac {dC}{d \theta})= F(\theta) - Q(\theta)C(\theta)
$$

![[Pasted image 20210721132303.png]]
### Decay or Growth 
#equations 

![[Pasted image 20210721132315.png]]

$$
Q(\theta)=\frac{F(\theta)}{C}
$$

#important 
Engineering experience and filed studies indicate that an outdoor air supply of approx 2- cfm per person is very likely to provide acceptable perceived indoor air quality in office spaces. Even though we are examining job shops. 

### Airflow through large intentional Openings 
This is #important for the large warehouse doors for both buildings

$$
Q = 776 C_D A \sqrt {2 \Delta p/ \rho}
$$

![[Pasted image 20210721132956.png]]

### Natural Ventilation Guidelines 

Opening locations 
- Windows should be located inopposing pressure zones. Two openings on opposite sides of a space increase ventilation flow 
- Vertical distance between openings is required to take advantage of stack effect. The greater the vertical distance, the greater the ventilation rate.

Opening Characteristics 
- Greatest flow per unit area of total opening is obtained by inlet and outlet openings of nearly equal areas 

#skipped over residential ventilation 

## Commercial and institutional air leakage 



