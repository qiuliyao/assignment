# one_dimensional_heat_diffusion_equation

- assignment 2
  
- For one dimension heat diffusion equation, ∂T/∂t=∂^2T/∂x^2;
- its initial condition is the normal distribution: T0=A*exp(-(x-0.5*L).^2/(0.1*L)^2 ) ;
- the Neumann boundary condition is ∂T/∂x=0 (x=0,x=L);
- We use the FTCS differential format, which is the Euler forward in time central in space, to get a numerical solution.
- K is the thermal diffuction coefficient(m^2/s); L is the length we simulate.

  Changing the initial condition, the numerical solution get stable more quickly than the cosine fuction. And the final temperature is more high.
