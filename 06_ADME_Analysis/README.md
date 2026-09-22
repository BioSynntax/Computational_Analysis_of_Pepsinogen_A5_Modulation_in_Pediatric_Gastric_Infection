# ADME Analysis

## Overview

This section presents the in silico ADME and drug-likeness analysis of five phytocompounds investigated against Pepsinogen A5.

## Compounds Analyzed

The following phytocompounds were evaluated:

1. Decursin
2. Catechin
3. Quercetin
4. Irisolidone
5. Glabridin

## ADME and Drug-Likeness Results

| Compound | MW (g/mol) | TPSA (Å²) | Consensus LogP | H-Bond Acceptors | H-Bond Donors | GI Absorption | BBB Permeant | P-gp Substrate | Lipinski Violations | Bioavailability Score |
|---|---:|---:|---:|---:|---:|---|---|---|---:|---:|
| Decursin | 328.36 | 65.74 | 2.85 | 5 | 0 | High | Yes | No | 0 | 0.55 |
| Catechin | 290.27 | 110.38 | 0.85 | 6 | 5 | High | No | Yes | 0 | 0.55 |
| Quercetin | 302.24 | 131.36 | 0.95 | 7 | 5 | High | No | No | 0 | 0.55 |
| Irisolidone | 314.29 | 89.13 | 2.04 | 6 | 2 | High | No | No | 0 | 0.55 |
| Glabridin | 324.37 | 58.92 | 3.52 | 4 | 2 | High | Yes | Yes | 0 | 0.55 |

## Solubility

Predicted ESOL solubility classes were:

| Compound | ESOL Solubility Class |
|---|---|
| Decursin | Soluble |
| Catechin | Soluble |
| Quercetin | Soluble |
| Irisolidone | Soluble |
| Glabridin | Moderately soluble |

## Pharmacokinetic Predictions

All five compounds showed predicted high gastrointestinal absorption.

Predicted blood–brain barrier (BBB) permeability was observed for Decursin and Glabridin, whereas Catechin, Quercetin, and Irisolidone were predicted as non-BBB permeant.

P-glycoprotein (P-gp) substrate predictions were positive for Catechin and Glabridin.

## CYP450 Enzyme Predictions

The SwissADME predictions indicated differences in potential CYP enzyme interactions among the compounds. These predictions included CYP1A2, CYP2C19, CYP2C9, CYP2D6, and CYP3A4.

These computational predictions should be interpreted as preliminary pharmacokinetic indicators and not as experimentally confirmed enzyme inhibition.

## Lipinski's Rule of Five

None of the five analyzed compounds showed a Lipinski rule violation in the SwissADME output.

## Bioavailability

All five compounds had a predicted bioavailability score of 0.55.

## Boiled-Egg Analysis

A SwissADME Boiled-Egg analysis was performed to visualize the predicted gastrointestinal absorption and blood–brain barrier permeability characteristics of the compounds.

The Boiled-Egg plot is included in this directory as a supporting visualization.

## Workflow

1. Selection of docked phytocompounds
2. Retrieval/preparation of ligand structures
3. SwissADME-based physicochemical analysis
4. Evaluation of lipophilicity and polarity
5. Prediction of gastrointestinal absorption
6. Prediction of BBB permeability
7. P-glycoprotein substrate prediction
8. CYP450 interaction prediction
9. Lipinski rule evaluation
10. Boiled-Egg analysis

## Tool Used

- SwissADME

## Output

The ADME analysis provides computational predictions of physicochemical properties, drug-likeness, gastrointestinal absorption, BBB permeability, P-gp substrate status, CYP450 interactions, and solubility characteristics of the selected phytocompounds.

## Note

All ADME and pharmacokinetic values are computational predictions. They should not be interpreted as experimentally established pharmacokinetic or therapeutic properties. Experimental studies are required for validation.
