BNSim2
======

BNSim is an open-source, parallel, stochastic, and multi-scale modeling
platform which integrates various simulation algorithms, together with
chemotaixs, quorum sensing, and biofilm models in a 3D environment.

BNSim is developed by CMU SLD Group, and released under GPLv2 license
Please check http://www.ece.cmu.edu/~sld/ for more information

BNSim is developed using C++ and pthread under Linux and Mac OS

If you use it or part of it for your work, please cite
Wei, Guopeng, Paul Bogdan, and Radu Marculescu. "Efficient Modeling and
Simulation of Bacteria-Based Nanonetworks with BNSim." Selected Areas in
Communications, IEEE Journal on 31.12 (2013): 868-878. Note that if you use
Eclipse, please mannually add the link to pthread library, and use -std=c++11
for compilation. 

You can build the program easily by importing the source files into 
Xcode or Eclipse or any other IDE you like.

The simulator is fully extensible, you can add regulatory networks in the 
library, and different cell types in the zoo. 
