# Results and Findings

## Overview

This section summarizes the computational results obtained during the structural and molecular analysis of human Pepsinogen A5 and its interactions with selected phytochemicals. The project integrates protein modeling, structure validation, computational activation, molecular docking, interaction analysis, and ADME prediction.

## 1. Protein Modeling

The three-dimensional structure of human Pepsinogen A5 was modeled using MODELLER 10.8.

Five structural models were generated and assessed using the DOPE and GA341 scores.

| Model | DOPE Score | GA341 Score |
|---|---:|---:|
| HUMA.B99990001.pdb | -12768.93555 | 1.00000 |
| HUMA.B99990002.pdb | -12734.36816 | 1.00000 |
| HUMA.B99990003.pdb | -12682.51855 | 1.00000 |
| HUMA.B99990004.pdb | -12753.55469 | 1.00000 |
| HUMA.B99990005.pdb | -12730.47461 | 1.00000 |

HUMA.B99990001.pdb had the lowest DOPE score among the five models. The model-selection decision should be confirmed against the structure actually used in downstream analyses.

## 2. Structure Validation

The modeled protein structure was assessed using the following computational tools:

- Ramachandran plot analysis
- ProSA
- QMEAN
- ProQ

These tools were used to assess different aspects of the modeled structure's stereochemical and predicted structural quality. Individual numerical results and plots are documented in `03_Structure_Validation/`.

## 3. Pepsinogen Activation and Preparation

The modeled Pepsinogen A5 structure underwent computational processing that included:

1. Removal of the first 44 amino acids.
2. Protonation at pH 2.
3. Energy minimization.

The resulting activated and minimized structure was prepared for use as the receptor in molecular docking.

## 4. Molecular Docking

Five phytochemicals were evaluated using AutoDock. The predicted docking scores are summarized below.

| Compound | Binding Energy (kcal/mol) | Hydrogen Bonds |
|---|---:|---:|
| Decursin | -9.60 | 0 |
| Catechin | -9.20 | 3 |
| Quercetin | -9.19 | 3 |
| Irisolidone | -8.90 | 2 |
| Glabridin | -7.61 | 1 |

Decursin had the most negative predicted binding energy among the five compounds, followed by Catechin and Quercetin. Catechin and Quercetin each formed three reported hydrogen bonds.

These scores are computational predictions and should not be interpreted as experimentally measured binding affinities or proof of biological activity.

Detailed docking data are available in `Docking_Results/Docking_Summary.csv`.

## 5. Protein–Ligand Interaction Analysis

Protein–ligand interactions were examined using Discovery Studio.

Reported interacting residues included TRP 57, MET 47, ILE 58, PHE 44, GLN 45, GLY 43, and VAL 62, among others, depending on the compound.

The number and identities of hydrogen bonds and other interacting residues varied across the five docked compounds. Compound-specific interaction results are documented in `05_Molecular_Docking/Interaction_Analysis/`.

## 6. ADME Analysis

SwissADME was used to predict selected physicochemical and pharmacokinetic properties of the phytochemicals.

| Compound | TPSA | Consensus Log P | GI Absorption | BBB Permeant | Lipinski Violations |
|---|---:|---:|---|---|---:|
| Decursin | 65.74 | 2.85 | High | Yes | 0 |
| Catechin | 110.38 | 0.85 | High | No | 0 |
| Quercetin | 131.36 | 0.95 | High | No | 0 |
| Irisolidone | 89.13 | 2.04 | High | No | 0 |
| Glabridin | 58.92 | 3.52 | High | Yes | 0 |

All five compounds had zero predicted Lipinski rule violations and a SwissADME bioavailability score of 0.55 in the analyzed dataset.

These predictions are useful for preliminary compound profiling but do not establish actual absorption, safety, bioavailability, or therapeutic efficacy.

The summarized data are available in `ADME_Results/ADME_Summary.csv`.

## 7. Overall Findings

The computational workflow generated a modeled Pepsinogen A5 structure, evaluated its predicted structural quality, prepared an activated structure, and compared the predicted docking scores and interactions of five phytochemicals.

Decursin showed the most negative docking score in this dataset, while Catechin and Quercetin also showed favorable predicted docking scores and multiple hydrogen bonds. SwissADME predictions provided additional preliminary information about the physicochemical and pharmacokinetic properties of these compounds.

These findings identify candidates for further investigation; they do not establish inhibition of pepsin activity or efficacy against pediatric gastric disorders.

## 8. Limitations

- Protein modeling and structure-quality assessments are computational.
- Docking scores are estimates and do not confirm binding experimentally.
- Predicted protein–ligand interactions require experimental confirmation.
- ADME results are in silico predictions, not clinical or experimental measurements.
- Enzyme inhibition, biological activity, safety, and therapeutic potential were not established by these analyses.

## 9. Future Directions

Future work could include experimental enzyme-inhibition assays, biochemical validation of compound–protein interactions, and additional computational studies to investigate the predicted effects of selected phytochemicals.

## Related Project Sections

- `02_Protein_Modeling/` — MODELLER results
- `03_Structure_Validation/` — structural quality assessment
- `04_Pepsinogen_Activation_and_Preparation/` — activation and minimization
- `05_Molecular_Docking/` — docking and interaction analysis
- `06_ADME_Analysis/` — SwissADME predictions
- `07_Visualization/` — project visualizations

## Reproducibility

Summary tables are provided in this folder. Detailed outputs, figures, and analysis files are maintained in their respective project directories. All reported values should be interpreted in the context of the computational methods used.
