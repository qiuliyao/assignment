# one_dimensional_heat_diffusion_equation

- For one dimension heat convection equation: ∂T/∂t+u*∂T/∂x=0;
- its initial condition is the normal distribution: T0=A*exp(-(x-0.5*L).^2/(0.1*L)^2 ) ;
- the boundary condition is T(1,t)=T(n-1,t),T(n,t)=T(2,t);
- L is the length we simulate;
- u=0.1cm/s;
- lambda=u*dt/dx, lambda is the courant number, and it must be smaller than 1.
  
- We first use the CTCS differential format, which is the central in time central in space, to get a numerical solution. Before that, the first step uses the FTCS differential format.

At the first 4 seconds, the temperature is moving regularly. After that, it becomes more irregular and slower. 

