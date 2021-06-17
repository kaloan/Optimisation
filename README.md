# Optimisation

Some basic optimisation algorithms implemented in Mathematica.

Gradients and Hessians are taken explicitly, not numerically approximated.

Conjugate gradient is implemented only for the linear case.

**Warning** Newton's Method assumes that the Hessian is positive definite. A possible enchancement would be to check if that is true every few steps and whenever it is not positive definite, to use gradient descent for some nuber of steps. 
