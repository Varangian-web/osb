# 540 and Galaxy HVAC modeling equations and notes
-------
#ASHRAE 
Currently these buildings are experiencing higher than normal temperatures 

**Objectives

1. Understand the steady state model of the buildings based on the navier stokes equations #model 
2. Look into ASHRAE to find other equations and concepts that would prove useful #ASHRAE
3. Get data from buildings to incorporate into the model #HVACdata
4. Make conclusions to see if model is accurate 
5. Improve on model possibly 
6. Gather logical ideas to either improve aspects of the AHU within the HVAC system 
7. Prove those ideas within the created model
8. Implement on a large scale with the help of maintenance and management 



The following notes are based on Objective 1

Based on equations of mass, momentuem, flow direction, energy (Navier Stokes) and contaimant distributions 

![[ASHRAE_handbook_fundamental.pdf]]

To perfom the model, the basic steps would include 

1. Create the geometry of the simulation environment #model [[ASHRAE NOTES CH13]]
2. Identify heat sources and what method of heat transfer they engage in [[ASHRAE NOTES CH4]]
	1. May be possible to incorporate number of people as heat sources since they mov
		1. Most likely an extra step that wouldn't be necessary, just wanted to mention for accuracy 
3. Identify points of inflow and outflow of air #HVACdata. This will conncet to #ASHRAE concepts that deal with the various requirement of contaminants and other compliances that need to be followed.
4.  Define the various surcaces and columes for the boundary conditions 
5.  Now we can exceute the simulation 
6.  Determine whether or not the simulation was accurate based on previous knowledge 
7.  Compare with data gathered 
8.  If model does not match data, repeat the cycle until the desired accuracy of the model is achieved.


In-depth planning for simulation modeling #model 

You can also reference 
![[Chan_W_Navier-Stokes_Simulation_of_Air-Conditioning_Facility_of_A_Large_Modern_Computer_Room.pdf]]

Chapters completed 
#todo 
 - [x] CH 1 
 - [ ] CH 2
 - [ ] CH 3
 - [x] CH 4
 - [ ] CH 5
 - [x] CH 6
 - [ ] CH 7
 - [ ] CH 8
 - [x] CH 9
 - [x] CH 10
 - [ ] CH 11 
 - [ ] CH 12
 - [ ] CH 13
 - [ ] CH 14
 - [ ] CH 15 
 - [ ] CH 16
 - [ ] CH 17 
 - [ ] CH 18 
 - [ ] CH 19 
 - [ ] CH 20 
 - [ ] CH 21 
 - [ ] CH 22 
 - [ ] CH 23 
 - [ ] CH 24  