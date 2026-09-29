# Sequence Analysis

This section contains the sequence-level analysis of human Pepsinogen A5 performed prior to three-dimensional protein modeling.

## Target Protein

- **Protein:** Human Pepsinogen A5
- **Sequence length:** 128 amino acids
- **Sequence format:** FASTA
- **Analysis tool:** ExPASy ProtParam

## Sequence Analysis Workflow

1. Retrieval of the human Pepsinogen A5 protein sequence
2. Preparation of the protein sequence in FASTA format
3. Physicochemical characterization using ExPASy ProtParam
4. Evaluation of protein stability, hydropathy, and charge-related properties
5. Use of the characterized sequence for subsequent structural modeling

## ProtParam Results

| Parameter | Result |
|---|---:|
| Number of amino acids | 128 |
| Molecular weight | 13,321.92 Da |
| Theoretical pI | 3.58 |
| Negatively charged residues | 13 |
| Positively charged residues | 2 |
| Instability index | 47.94 |
| Aliphatic index | 90.62 |
| GRAVY | 0.245 |

## Extinction Coefficient

The calculated extinction coefficient at 280 nm was:

- **10,220 M⁻¹ cm⁻¹** assuming all cysteine residues form cystines
- **9,970 M⁻¹ cm⁻¹** assuming all cysteine residues are reduced

## Estimated Half-Life

The estimated half-life reported by ProtParam was:

- **30 hours** in mammalian reticulocytes, in vitro
- **>20 hours** in yeast, in vivo
- **>10 hours** in *E. coli*, in vivo

## Output Files

- `Pepsinogen_A5_sequence.fasta` – protein sequence used for analysis
- `Results/Expasy_ProtParam.pdf` – complete ExPASy ProtParam output

## Downstream Application

The characterized Pepsinogen A5 sequence was subsequently used as the input for three-dimensional protein modeling using MODELLER.

## Software and Resources

- ExPASy ProtParam
- FASTA
- UniProt
- MODELLER
