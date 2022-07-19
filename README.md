## Computational Assignment CHE221

In this Assignment I have found a relation between x (mole ratio) of a substance in a binary mixture and temperature when pressure is kept constant (we know pressure beforehand)

### Degree Of Freedom Analysis

Through DOF analysis we know that this system has 2 degrees of freedom so if we fix two thermodynamic coordinates than we will be able to calculate every other variable.

### Current Problem

We already knew pressure of the system and we defined x1 between 0 and 1 so we defined two variables than every other variable can be calculated. So we are trying to calculate temperature by using **Modified Roult’s Law** and **Antoine Equation.** By adding roults law equations for both the substances we eliminated y1 and y2, now gamma1 and gamma2 are function of pressure, temperature, and x. And P1sat is function of temperature this means the only variable in the problem is temperature. But this equation non linear in nature so we have to use an iterative approach to obtain the solution. As the approach explained in the tutorial solution video is of very similar kind I worked in the line of this. I used the same concept and applied it the Matlab and obtained significantly

### correct results.

For the initial guess of temperature, I used linear interpolation technique and calculated temperature for both the substances considering total pressure because of that substance and then using linear interpolation of two results obtained.

### Error Analysis

The model reached a quite acceptable result as seen on the plots obtained. We typically reached the experimental values by using the theoretical models.

### Plots
![Plot 1](https://drive.google.com/uc?id=1qu7Zh9tNh7i7K0FVMRsZWqPyRGjm1Wsj)

![Plot 2](https://drive.google.com/uc?id=1ny9no5E-7gElYVUlIZpppEbPpRqHhREf)
