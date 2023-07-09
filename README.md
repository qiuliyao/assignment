# one dimensional heat diffusion and convection equation

- For one dimension heat convection equation: ∂T/∂t+u*∂T/∂x=K∂^2T/∂x^2;
- its initial condition is the normal distribution: T0=A*exp(-(x-0.5*L).^2/(0.1*L)^2 ) ;
- the boundary condition is dT/dx(x=0,x=L)=0;
- L is the length we simulate;
- u=0.1cm/s;
- K is thermal diffuction coefficient;
- lambda=u*dt/dx, lambda is the courant number, and it must be smaller than 1;

  
The temperature fells very fast. After 0.03 seconds it becomes stable.
