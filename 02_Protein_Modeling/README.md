# Protein Modeling

This section describes the three-dimensional structural modeling of human Pepsinogen A5 using MODELLER.

## Target Protein

- **Protein:** Human Pepsinogen A5
- **Sequence length:** 128 amino acids
- **Modeling software:** MODELLER 10.8
- **Sequence identity:** 98.438%

## Modeling Workflow

1. Human Pepsinogen A5 sequence was prepared in FASTA format.
2. Homology-based three-dimensional protein modeling was performed using MODELLER.
3. Five structural models were generated.
4. The generated models were assessed using the DOPE and GA341 potentials.
5. The model with the lowest DOPE score was considered for downstream structural analysis.

## Model Assessment

| Model | MolPDF | DOPE Score | GA341 Score |
|---|---:|---:|---:|
| HUMA.B99990001.pdb | 706.84064 | -12768.93555 | 1.00000 |
| HUMA.B99990002.pdb | 709.58173 | -12734.36816 | 1.00000 |
| HUMA.B99990003.pdb | 658.88940 | -12682.51855 | 1.00000 |
| HUMA.B99990004.pdb | 608.88837 | -12753.55469 | 1.00000 |
| HUMA.B99990005.pdb | 675.36011 | -12730.47461 | 1.00000 |

## Selected Model

Among the five generated models, **HUMA.B99990001.pdb** showed the lowest DOPE score:

**DOPE score: -12768.93555**

The GA341 score was **1.00000** for all five models.

The selected model was used for subsequent structural analysis and protein activation/preparation.

## Model Information

- **Residues:** 128
- **Real atoms:** 932
- **Static restraints:** 10,545
- **Sequence identity:** 98.438%

## Output Files

- `Pepsinogen_A5_Model.pdb` – protein structure used for downstream analysis
- `Results/model-single.log` – complete MODELLER output log
- `Results/Modeling_Results.txt` – summarized modeling results

## Software

- MODELLER 10.8
