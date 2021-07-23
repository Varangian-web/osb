# Energy Estimating and Modeling Methods 
## Intro
--- 
To create your model you'll need to have 
- input variables 
- System structure and parameters/properties
- Outputs

There are two broad approaches to the modeling of the system 

### Forward Approach 
The objective is to predict the output variables of a specified models with known structure. The approach is ideal in the preliminary design and analysis stages.
Includes:
- Building geometry 
- geographical location
- peak and average energy use the building 

#example 

government-developed simulation codes such as 
- BLAST 
- DOE-2
- Energy Plus 

### Data Driven Approach
This approach contains the know inputs/outputs variables which are measured. The goal is to determine a mathematical description of the system and to estimate system parameters 

![[Pasted image 20210721142215.png]]
![[Pasted image 20210721142237.png]]


Heat -Balance Method 

Peciewise-linear representation of the system know as a control profile 

#equations 
$$
q_{sys_{j}}= a + bt_{a_{j}}
$$

Substitue the equation above into 

![[Pasted image 20210721142510.png]]

Solving for zone air temperature [[ASHRAE NOTES CH18]]

The equation must be solved simultaneously with the interior and exterior surface heat balance equations 

![[Pasted image 20210721142610.png]]

### Heat transfer

The following provides a convenient and general model to calculate the heat transferred to the fluid:

$$ 
q_{fluid}=[]
$$

![[Pasted image 20210721144302.png]]

