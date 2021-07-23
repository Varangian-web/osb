

[Boussinesq Approximation Definition (comsol.com)](https://www.comsol.com/multiphysics/boussinesq-approximation)

Using the boussinesq approximation 

**Boussinesq approximation** is a way to solve nonisothermal flow such as natural convection problems, without having to solve for the full compressible formulation of the Navier-Stokes equation


The Navier-Stokes equations govern the motion of fluids. for a general case of a compressible fluid, this is 
#equations 
$$
\rho (\frac{\partial u}{\partial t}+u \cdot \nabla u)=-\nabla p + \nabla \cdot((\mu +(\nabla u)^T)- \frac 2 3 \mu(\nabla \cdot u)I)+ \rho g
$$
Where 
u = fluid velocity 
p = fluid pressure
rho = fluid density
mu - the fluid dynamic viscosity
I = identity matrix
g = accerleration due to gravity


Along with the continuity equation 

$$
\frac 1 \rho \frac {D \rho}{Dt} + \nabla \cdot u = 0
$$

But for the Boussinesq approximation, it states that the density variation is only important in the buoyancy term, rho times gravity can be neglected in the rest of equation which yields

$$
\rho_0 (\frac{\partial u}{\partial t}+u \cdot \nabla u)=-\nabla p + \nabla \cdot((\mu +(\nabla u)^T)- \frac 2 3 \mu(\nabla \cdot u)I)+ \rho g
$$

Under the approximation , the continuity equation reduces to

$$
\nabla \cdot u = 0
$$

 This is because the magnitude of  
 $$
\frac 1 \rho \frac {D \rho}{Dt} 
$$
 is extremely small with respect to the velocity gradient 
 
 The the diffusion term can be re-written and so can the bouyancy term
 $$
 \nabla \cdot((\mu +(\nabla u)^T \to \mu \nabla^2u
 $$
 $$
 u \to (\rho_0 + \Delta\rho)g
$$
where
$$ \Delta \rho = \rho - \rho_0
$$