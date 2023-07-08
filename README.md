# one_dimensional_heat_diffusion_equation

- For one dimension heat diffusion equation, ∂T/∂t=∂^2T/∂x^2;
- its initial condition is the normal distribution: T0=A*exp(-(x-0.5*L).^2/(0.1*L)^2 ) ;
- the Neumann boundary condition is ∂T/∂x=0 (x=0,x=L);
- K is the thermal diffuction coefficient(m^2/s); L is the length we simulate.
- We first use the FTCS differential format, which is the Euler forward in time central in space, to get a numerical solution. Then we use the BTCS differential format, Euler Backword in time central differencing in space.

FTCS differential format is explicit but BTCS format is implict. At fist, the explicit format is faster, but after a few time, they became the same and are stable at almost the same time. 
  
