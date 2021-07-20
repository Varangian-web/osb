# Meshing 
[[ASHRAE NOTES CH13]]
The finite element analysis of various structures with the properties of heat transfer will be the defining mesh that is created from the nodes within the buildings

1. Making the mesh will depend on multiple things
	1. Size of the mesh
	2. how will you define the area of each mesh
		1. Shape ![[Pasted image 20210720081936.png]]
	3. Initial conditions of the nodes 
	4. Define the level of grid independence from the flow field solution 
		1. ![[Pasted image 20210720082046.png]]
	5. Define the boundary conditions 
		1. Dirichlet: variable values specified at the boundary node
		2. Nuemann: Variable derivatives that are required tat the boundary, and the boundary condition must be discretized to provide the required equation
		3. ![[Pasted image 20210720082729.png]]
	6. Run the simulation 
	7. Update simulation in regards to improved data 
	8. Verify results with secondary model