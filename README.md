# Computational Analysis of Dynamic Allostery and Control in the SARS-CoV-2 Main Protease
Processed data and figure genration codes for a project on an Elastic Network Model analysis of the SARS-CoV-2 main protease (M<sup>pro</sup>, aka 3CL<sup>pro</sup>).
See a [preprint](https://www.biorxiv.org/content/10.1101/2020.05.21.105965v1) in bioRxiv.

## PDB
We used [6LU7](https://www.rcsb.org/structure/6LU7) X-ray crystallographic structure of the main protease to construct apo (ligand-free), holo1 (one ligand present) and holo2 protein forms (two ligands present, native form).
Note: all water molecues (`H2O`) were removed from all protein stucture PDB files.

## Software
ENMs were generated and processed in [Durham Dynamic Protein Toolbox](https://sourceforge.net/projects/durham-ddpt/), 'DDPT' for short, an open-source FORTRAN based protein analysis toolbox.

## Data
1. Cross-correlation of motion 
2. 1-point mutaional scan: relative change of fluctuation Gibbs free energy; ligand dissocaition contant ratio - in response ENM modifications.
3. 2-point mutational scan: relative change of fluctuation Gibbs free energy; ligand dissocaition contant ratio - in response ENM modifications.
 
\dataset{6lu7_freeEn.xlsx}{Computationally calculated fluctuation Gibbs free energy per mode of 6LU7 apo, holo1 and holo2 ENM forms over the first real 100 fluctuation modes.}

\dataset{6lu7_cross-cor_apo.xlsx}{Cross-correlation of motion and residue-reside distance map for 6LU7 apo ENM over the first real 25 fluctuation modes.}

\dataset{6lu7_dist_apo.xlsx}{Residue-reside (\Calpha{} nodes) distance map for 6LU7 apo ENM.}

\dataset{6lu7_cross-cor_holo1.xlsx}{Cross-correlation of motion and residue-reside distance map for 6LU7 holo1 ENM over the first real 25 fluctuation modes.}

\dataset{6lu7_dist_holo1.xlsx}{Residue-reside (\Calpha{} nodes) distance map for 6LU7 holo1 ENM.}

\dataset{6lu7_cross-cor_holo2.xlsx}{Cross-correlation of motion and residue-reside distance map for 6LU7 holo2 ENM over the first real 25 fluctuation modes.}

\dataset{6lu7_dist_holo2.xlsx}{Residue-reside (\Calpha{} nodes) distance map for 6LU7 holo2 ENM.}

\dataset{6lu7_1D-apo.xlsx}{1-point mutational scan results for 6LU7 apo over the first real 25 fluctuation modes.}

\dataset{6lu7_1D-allo.xlsx}{1-point mutational scan results for global allosteric control in 6LU7 ENM over the first real 25 fluctuation modes.}

\dataset{6lu7_2D-apo_kRk=0_25.xlsx}{2-point mutational scan results for 6LU7 apo over the first real 25 fluctuation modes at $k_R/k$=0.25.}

\dataset{6lu7_2D-apo_kRk=4_00.xlsx}{2-point mutational scan results for 6LU7 apo over the first real 25 fluctuation modes at $k_R/k$=4.00.}

\dataset{6lu7_2D-allo_kRk=0_25.xlsx}{2-point mutational scan results for global allosteric control in 6LU7 ENM over the first real 25 fluctuation modes at $k_R/k$=0.25.}

\dataset{6lu7_2D-allo_kRk=4_00.xlsx}{2-point mutational scan results for global allosteric control in 6LU7 ENM over the first real 25 fluctuation modes at $k_R/k$=4.00.}

## Code
1. Cross-correlation and distance map
2. 1-point mutational scan map (apo and allo)
3. 2-point mutational scan map (apo and allo)
