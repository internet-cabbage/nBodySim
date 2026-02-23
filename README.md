This is a brute force approach to solving the N body problem computationally. 

It works via producing ODE equations of motion for the various bodies, and solving it computationally using scipy.solve_ivp(). It can solve N body problems very accurately, but is not very efficient for large values of N.
