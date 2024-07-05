# OpenFOAM_solvers

OpenFOAM, being an Open source software facilitates new solver creation by employing a C++ framework that provides classes for defining equations, discretization schemes, and solvers. Users can extend functionality by customizing ,leveraging the existing solvers without rewriting core components, enabling rapid development and integration of new solvers.

Within OpenFoam_solvers, icofoam_temp presents a new solver new_icoFoam with the temperature attribute. Additionally, we solve one of the basic tutorial cases, cavity using the new solver.
Similarly, a new solver, myLaplaceFoam was created from a previously available solver scalarTransportFoam, which we are using to solve two test cases, i in 1D and the other in 2D.
