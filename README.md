# Elastic dipole calculation with LAMMPS

## Goal
The goal of this code is to evaluate the elastic dipole of one substitutional solute atom

## Elastic dipole

The elastic can be determined knowing the volume V of the box and the average residual stresses induced by the solute atom over the box volume :

$$P_{ij}^0 = -V \langle \sigma_{ij}\rangle$$

## How to use

1. Change the elastic constant of the solvant and the potential-related lines in the code and launch the calculation
2. The values of the symmetric tensor are in the .txt file generated
