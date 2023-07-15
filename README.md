# README

The 'gate_count_comparison.txt' file contains data for Figure 10.

Arrays named 'ri_orbital' contain indices which the UCC factor of rank-i acts on, e.g. r4_orbital array contains the indices 12, 10, 9, 4 of the unoccupied
orbitals, and indices 29, 24, 20, 14 of the occupied orbitals. A definite count of the CNOT gates require a set of specific indices.

The standard_correction array, FEB array, and the LCU_correction store the exact gate count of the CNOT gates for each UCC factor circuit whose ranks range from
two to nine, given by the arrays ri_orbitals previously.
