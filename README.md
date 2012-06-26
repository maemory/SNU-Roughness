SNU-Roughness
=============
Repository for SNU-SU 2012 Fluent simulations of flat plate investigating wall roughness and pressure gradient combined effects.

There are three folders representing threee test cases, one each for:
- zero pressure gradient
- adverse pressure gradient
- favorable pressure gradient

The pressure gradient is controlled by changing the geometry of the top wall by plus or minus 4 degrees.

GAMBIT
======
The gambit database files (*.dbs) can be used to load/edit the mesh generation process.

FLUENT
======
The simulations ran very quickly, though setup files were not stored for each case. The basic parameters for the simulation are:
INFLOW: 11.5 m/s
ROUGH_WALL: element height = 0.0004 m
TURB MODEL: k-omega
TURB BC:
- turb intensity = 1%
- viscosity ratio = 5

No other values needed to be specified.

TECPLOT
=======
Tecplot data files (fluid, no surfaces) are found in .dat files for both rough and smooth wall cases. the tecplot folder contains layout file to post process contours as well as extract and visualize profile data.
