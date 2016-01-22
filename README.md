This is a straightforward 2D finite volume code to solve MHD problems.

It uses a 2nd order Runge Kutta time integration method and a choice of Roe/HLLD Riemann solvers.

The data is stored in multidimensional arrays allocated using the Template Numerical Toolkit.

Output is in HDF5 or binary format.

Several initial conditions are provided, e.g. blast waves, jet and MAES.