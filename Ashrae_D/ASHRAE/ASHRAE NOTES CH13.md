[[ASHRAE - Objective 1]]

# Indoor Environmental modeling

## Intro 
----
It was mentioned that a strong grasp of the fundamental building physics and detailed knowledge of the building space being modeled are necessary. Reference 
[[ASHRAE NOTES CH 1]],[[ASHRAE NOTES CH3]],[[ASHRAE NOTES CH4]],[[ASHRAE NOTES CH6]],[[ASHRAE NOTES CH9]],[[ASHRAE NOTES CH11]],[[ASHRAE NOTES CH14]],[[ASHRAE NOTES CH15]]

#important 
When modeling existing buildings, taking measurements may significantly improve the modeling effort.

This section will present two common indoor environmental modeling methods to calculate the airflows and contamination concentration using CFD and multizone network airflow modeling.

Using #Navier-Stokes [equation](https://www.grc.nasa.gov/www/k-12/airplane/nseqs.html)  #equations to obtain a detailed flow field and pollutant concentration distribution within a space, is possibly the best method for the [[ASHRAE - Objective 1]].

## Navier-Stokes 
----
THe Reynolds number is the ratio of the scaling of the inertia of the flow to the viscous forces in the flow.
The Prandtl number is is the ratio of the viscous stresses to the thermal stresses.

#Navier-Stokes 
Strengths of the model:
- details 
	- airflow
	- temperature 
	- contaminant concentration [[ASHRAE NOTES CH10]]

Weakness of model
- results require significant time 
- time cost typically limits CFD applications 
	- single rooms 
	- steady state solutions 

![[Pasted image 20210720070532.png]]
A direct solution of differential equations for various flow regimes among rooms is not possible, but a numerical method can be applied. 

Using a multizone ariflow and pollutant transport modeling can yield  a better macroscopic view of a building by solving a network of mass balance equations to obtain airflows and average pollutant concentrations in different zones of a whole building.

### Reynolds-Averaged Navier-Stokes(Approaches)

The most intuitive approach to calculate Reynolds stresses is to adopt the mixing-length hypotheses 

#conditions 


#  CFD Modeling Approaches 

## 1. Planning
---
	1. This is the most important step 
		1. **Understand what is being investigated and what the outputs are desired to be analyzed**
	2. Decided whether to conduct a steady-state or transient simulation 
	3. Recognize that some flows are inherently unsteady.
	4. Last step of planning is determining how boundary conditions should be represented 

 ## 2. Steps for meshing and setting conditions of the computational fluid dynamics model 
----
1.  Define the geometry or 3D model of the environment
2.  Divide the region of interest into a large number of smaller regions. This will generate your meshing, gridding or discretization of the computational domain.[[Meshing]]
4. Inlet Boundary Conditions [[IBC]]
5. Outlet Boundary Conditions [[OBC]]
6. Wall/Surface Boundary Conditions [[WSBC]]
7. Symmetry Surface Boundary Conditions [[SSBC]]
8. Fixed sources and Sinks [[FSS]]
9. Verify that all volumes and sufaces are defined

## 3. Execution and improvement 
---
1.  Evaluate that the simulation and conduct quality checks to determine whether the CFD is complete and accurate 
2.  Analyze the simulation to extract the desired information 
3.  Modify the simulation with data gathered or better implementation of the model to produce a more accurate simulation 

### Computational Fluid Dynamics continued 
----
CFD will involve solving coupled partial differential equations, which must be worked simultaneously or successively. 

### Mathematical and Numerical Background 


Airflow in natural and built environments is predominantly 
 #conditions 
 - turbulent 
 - characterized by
	 - randomness 
	 - diffusivity [[ASHRAE NOTES CH6]] 
	 - dissipation 
	 - large Reynolds numbers [[ASHRAE NOTES CH3]][[ASHRAE NOTES CH6]]	

Indoor airflow, convective heat transfer and species dispersion are controlled by the governing equation for mass, momentum in each flow direction 

![[Pasted image 20210719105535.png]]

![[Pasted image 20210719105248.png]]

![[Pasted image 20210719110009.png]]

The total description of flow, therefore, consists of eight differential equations, which are coupled and nonlinear. These equations contain first and second derivatives that express the convection, diffusion, and source of the variables. The equations can also be numerically solved [see the section on Large Eddy Simulation (LES)]


![[Pasted image 20210719110151.png]]

## Multizone airflow modeling 

---
Theory is that the network airflow models idealize a building as a collection of zones:
- rooms 
- hallways 
- duct junctions

that are interconnected by:
- doors 
- windows
- fans 
- ducts 

The models will be assembled to describe a building that is connected by these zones and with the appropriate flow paths.

At any given time, the network zone is characterized by a single pressure. Using the simple hydrostatic relationship:
#equations 
$$
P+\rho g h=constant 
$$
With air density being determined by the equation of state 
$$
\rho = \frac {P}{(R_{air}T)}
$$
#important 
With P being the pressure, T being the temperature, and R_air being the gas constant of the air mixture. The gas constant is typically assumed to be that of dry air, but can function as constituents as well such as water vapor 


### Solution Techniques
#conditions 
1. Input zones and building geometry 
	This should only include enough detail to capture the necessary information 
	#example 

	![[Pasted image 20210719125950.png]]
	Incorporate the various zones for all the levels 
	![[Pasted image 20210719130721.png]]
2. Determine and specify building leakage
	Within the model set the doors within the build to open and place a pressurization fan in an exterior wall. Then pressurize the building 
	
3. Check stack effects 
	1. Do this by Removing the blower door fan from the model to specify a could outdoor  

4. Specify wind and wind pressure profiles 
5. Input air-handling systems
6. Specific contaminants 
7. Run sensitivity analysis 