# one_dimensional_heat_diffusion_equation
- assignment 1
  
- For one dimension heat diffusion equation, ∂T/∂t=∂^2T/∂x^2;
- its initial condition is a cosine fuction: T0=A*cos(1*x/L*pi) ;
- the Neumann boundary condition is ∂T/∂x=0 (x=0,x=L);
- its exact solution is T_exact = A*exp(-K*lambda^2*it*dt)*cos(lambda*x);
- We use the FTCS differential format, which is the Euler forward in time central in space, to get a numerical solution.
- K is the thermal diffuction coefficient(m^2/s); L is the length we simulate.
  
  we use the FTCS differential format, which is the Euler forward in time central in space, to get a numerical solution. And we compare it with the exact solution. They are very similar. They change fast in the beginning then get slower. And they become stable after the 40 seconds.
