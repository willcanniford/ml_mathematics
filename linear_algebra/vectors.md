# Vectors 
Linear algebra is capable of helping us to solve linear simultaneous equations through using vectors and matrices and performing certain operations on them. 

Another problem that we might be interested in using the linear algebra for is through the fitting of some parameters to a dataset; if you've able to successfully map the parameters to a dataset accurately, then that could be used in place of the actual data for additional calculations. 

While looking at a distribution of values of a singular variable, we can say that the distirbution can be defined by the mean of the population, as well as the variation that we see in that popualtion. These are two **parameters** that linear algebra could help us to estimate for a normal Gaussian distribution. 

While have an error function that gives a value, we use vectors to navigate the parameter space to find the optimal values for the parameters to minimise the error function. This appears to be the premise for gradient descent, whereby you are attempting to find minimums for the cost functions by navigating the calculus parameter space using a vector direction to improve your parameters. 

The space of all the parameters of a given function map out a spatial view, and then the vector can tell us how to move around that space. Given a 3 dimensional space, the vector [x, y, z] could tell us how to navigate that world; with the addition of time into a 4 dimensional space, we can then start to think as a vector that includes time: [x, y, z, t]. 

With optimisation we are trying to find a location in that parameter space where the 'badness' is minimised, the 'goodness' is maximised and the function is fitting the data the best it can be. We will want to work with vectors and then use calculus on those parameter spaces to find gradients in these 'contour maps' to find minima for the functions. 

> Vectors can be viewed as a list of numbers which describes some optimisation problem.They can be seen geometrically, numerically and algebraically. 

Plotting out the cost function across all values of the parameters produces a plane. Any point on this plane has a vector location which represents the value of the cost function given a set of parameters i.e. [2, 3] would be a position on the plane that describes f(x) = p1 * p2 * y; for the value of p1 = 2 and p2 = 3 what is the value of the function? That will give an additional dimension. 

Moving at right angles to the contour plane will enable the quickest optimisation of an equation where we are looking for the smallest error function. This makes sense as you are increasing/descreasing each parameter individually trying to work out their values quickly and the impact of that delta on the cost function. 

- - -

## [Operations with vectors]('./vector_operations.md)