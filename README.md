This directory includes the input files for Gromacs for the poly(D-lactic acid) and two copolymers containing L and D monomers.
The used force field, based on ref[1] was modified to be able to simulate copolymer structures. Namely, the tabulated potential for the backbone dihedrals was replaced by the Ryckaert-Bellemans function, which has the same parameters for both types of monomers. In addition, a new atom type was created for the D-type of monomer, to be able to properly distinguish CMAP parameters for each type of monomer. 

The files were also published as a part of Supplementary Information in Bacova, P.; Harmandaris, V.; Molina, S. I. Computational investigation of structural properties of poly(lactic acid) and its stereoisomers: shape, size and flexibility. Macromolecules 2025, in press. 


[1] McAliley, J. H.; Bruce, D. A. Development of Force Field Parameters for Molecular Simulation of Polylactide. Journal of Chemical Theory and Computation 2011, 7, 3756–3767, DOI: 10.1021/ct200251x
