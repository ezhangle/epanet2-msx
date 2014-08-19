epanet2-msx
===========

EPANET-MSX (Multi-Species eXtension) enables EPANET to model complex reaction schemes between multiple chemical and biological species in both the bulk flow and at the pipe wall. This capability has been included into both a stand-alone executable program as well as a toolkit library of functions that programmers can use to build customized applications.

EPANET-MSX requires a new input file that the user specifies the mathematical expressions that govern the reaction dynamics of the system being studied. This allows users the flexibility to model a wide range of chemical reactions of interest. Examples include:

 + the auto-decomposition of chloramines to ammonia,
 + the formation of disinfection by-products,
 + biological re-growth including nitrification dynamics,
 + combined reaction rate constants in multi-source systems, and
 + mass transfer limited oxidation-pipe wall adsorption reactions.

EPANET-MSX is distributed in a compressed zip file that contains a command line executable, several libraries of functions, and a User’s Manual. The executable can be used to run water quality analyses without any additional programming effort. The function library can be used in conjunction with the EPANET Programmer’s Toolkit to develop customized applications.


From the Repository owner:
--------------------------

The code in this repo is intended for compilation under linux systems. For other OS, please refer to the developer site at www.epa.gov for instructions.

Also note that this repo only includes the code for the computational engine and no graphical interface is supplied. CLI only!
