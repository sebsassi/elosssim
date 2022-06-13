Energy loss simulation database
===============================

This repository contains the data from molecular dynamics simulations of energy loss to crystal defects from nuclear recoils.

For compund materials there is one file for each element in the material, corresponding to the element of the recoiling nucleus.

The data files are formatted as follows:

1. The file begins with a header that contains the lengths of the rectangular cuboid unit cell defining the crystal lattice in the simulation coordinates.
2. The first data line contains two empty values, followed by the range of simulated recoil energies in eV.
3. The following lines contain the polar angle and azimuthal angle of the recoil direction in radians, followed by the energy loss values (in eV) for the simulated recoil energies in that direction.
