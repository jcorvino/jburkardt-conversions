# jburkardt-conversions
Conversions of various code repositories (https://people.sc.fsu.edu/~jburkardt/) from C++/MATLAB/FORTRAN to Python

**NOTE: THESE ARE INITIAL IDEAS AND SUBJECT TO CHANGE. NO WORK HAS BEEN COMPLETED YET.**


## Initial Project Ideas:

### 1. [BRENT](brent/)

BRENT was originally a FORTRAN77 library which contains algorithms for finding zeros or minima of a scalar function of a scalar variable, by Richard Brent. The methods do not require the use of derivatives, and do not assume that the function is differentiable. 

_I converted BRENT from FORTRAN 77 to Python._


### 2. [BROWNIAN_MOTION_SIMULATION](brownian_motion_simulator/)

BROWNIAN_MOTION_SIMULATION was originally a C++ library which simulates Brownian motion in an M-dimensional region, creating graphics files for processing by gnuplot. Brownian motion is a physical phenomenon which can be observed, for instance, when a small particle is immersed in a liquid. The particle will move as though under the influence of random forces of varying direction and magnitude. There is a mathematical idealization of this motion, and from there a computational discretization that allows us to simulate the successive positions of a particle undergoing Brownian motion.

_I converted BROWNIAN_MOTION_SIMULATION from C++ to Python._


### 3. [ZIGGURAT](ziggurat/)

ZIGGURAT was originally a MATLAB library which rapidly generates random variates from the uniform, normal or exponential distributions, by Marsaglia and Tsang. The uniform numbers are generated directly. The ziggurat method is used to compute the normal and exponential values. In the reference, the underlying generators are implemented "inline", invoking a function call only in exceptional cases. This results in very fast execution. In this implementation, the advantages of inline code are not used. All the routines and inline functions are isolated in a separate file, so that a user invokes them through the familiar library interface.

_I converted ZIGGURAT from MATLAB to Python_
