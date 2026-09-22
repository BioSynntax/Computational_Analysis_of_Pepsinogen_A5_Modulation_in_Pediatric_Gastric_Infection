# Molecular Docking

## Overview

This section presents the molecular docking analysis of selected bioactive compounds against the Pepsinogen A5 protein structure.

## Protein Target

**Pepsinogen A5**
Structure/Model: **F5GWT0_1FLH**

## Objective

The objective of molecular docking was to investigate the binding potential of selected ligands with Pepsinogen A5 and characterize their predicted binding interactions based on binding energy, hydrogen bonding, and interacting amino acid residues.

## Docking Results

| S. No. | Ligand      | Binding Energy (kcal/mol) | No. of H Bonds | H-Bond Distance (Å)          | Interaction Residues                                                                             |
| -----: | ----------- | ------------------------: | -------------: | ---------------------------- | ------------------------------------------------------------------------------------------------ |
|      1 | Decursin    |                     -9.60 |              0 | –                            | TRP 57, MET 47, ILE 58, PHE 44, PHE 18, LEU 59, PHE 63                                           |
|      2 | Catechin    |                     -9.20 |              3 | H1: 2.14; H2: 1.69; H3: 2.58 | LEU 56 (H1), ILE 58, GLN 45 (H2), GLY 43 (H3), PHE 44, VAL 62                                    |
|      3 | Quercetin   |                     -9.19 |              3 | H1: 1.90; H2: 1.84; H3: 2.67 | LEU 56 (H1), GLN 45 (H2), PHE 44, GLY 43 (H3), ILE 58, VAL 62                                    |
|      4 | Irisolidone |                     -8.90 |              2 | H1: 1.84; H2: 2.25           | ILE 16, PHE 18, VAL 27, VAL 62, PHE 63, TYR 32, PHE 44, GLN 45 (H1), MET 47, ILE 58, GLY 60 (H2) |
|      5 | Glabridin   |                     -7.61 |              1 | H1: 2.26                     | ILE 58 (H1), MET 47, GLY 60, VAL 62, PHE 44                                                      |

## Binding Interaction Analysis

The docking analysis showed favorable predicted binding energies for all five investigated ligands. Decursin showed a predicted binding energy of -9.60 kcal/mol, followed by Catechin (-9.20 kcal/mol) and Quercetin (-9.19 kcal/mol).

Catechin and Quercetin formed three predicted hydrogen bonds with the target structure. Irisolidone formed two hydrogen bonds, while Glabridin formed one. Decursin did not show a predicted hydrogen bond in the analyzed docking pose, although several amino acid residues were involved in its predicted interaction with the protein.

## Commonly Observed Interaction Residues

Several residues were observed across the docking poses, including:

* ILE 58
* PHE 44
* MET 47
* VAL 62
* GLY 60
* GLN 45
* LEU 56

These residues were associated with the predicted ligand-binding interactions and may contribute to stabilization of the docked complexes.

## Docking Workflow

1. Preparation of the Pepsinogen A5 receptor
2. Preparation of selected ligand structures
3. Molecular docking
4. Generation and evaluation of docking poses
5. Analysis of binding energies
6. Identification of hydrogen bonds
7. Identification of interacting amino acid residues
8. Visualization of ligand–protein interactions

## Software Used

* AutoDock
* Discovery Studio
* PyMOL

## Output

The docking analysis generated predicted ligand-binding poses, binding energy values, hydrogen-bond interactions, and interacting amino acid residues for the selected compounds.

## Note

Docking scores and predicted interactions represent computational estimates of ligand–protein binding and should not be interpreted as experimental binding affinities. Experimental studies are required to validate these computational findings.
