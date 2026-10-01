# Pepsinogen Activation and Preparation

This section describes the computational activation and preparation of human Pepsinogen A5 for molecular docking.

## Target Protein

- **Protein:** Human Pepsinogen A5
- **Starting structure:** Modeled Pepsinogen A5
- **Activation:** Removal of the first 44 amino acids
- **Protonation:** pH 2
- **Energy minimization:** Performed after activation

## Activation Workflow

The modeled Pepsinogen A5 structure was computationally processed
to obtain an activated pepsin-like structure.

The workflow included:

1. Selection of the modeled Pepsinogen A5 structure.
2. Removal of the first 44 amino acids.
3. Protonation of the structure at pH 2.
4. Energy minimization of the activated structure.
5. Preparation of the final structure for molecular docking.

## N-Terminal Cleavage

The first 44 amino acids were removed from the modeled
Pepsinogen A5 structure.

The resulting structure was used for subsequent protonation
and energy minimization.

## Protonation

The activated structure was protonated at **pH 2**.

This step was used to represent the acidic gastric environment
for the subsequent structural analysis.

## Energy Minimization

Energy minimization was performed on the activated structure.

The minimization step was used to reduce unfavorable
structural interactions before molecular docking.

## Output Structure

The final activated and minimized Pepsinogen A5 structure
was used as the receptor for molecular docking.

## Workflow

```text
Modeled Pepsinogen A5
        ↓
Removal of first 44 amino acids
        ↓
Activated Pepsinogen A5
        ↓
Protonation at pH 2
        ↓
Energy Minimization
        ↓
Activated and Minimized Structure
        ↓
Molecular Docking
