# EGLN1 (PHD2) evolution and functional-mutation analysis in guinea pig

Phylogenomics + protein-language-model study of whether guinea pig
(*Cavia porcellus*, a high-altitude-adapted hystricomorph rodent) carries
functional substitutions in EGLN1/PHD2, the cellular oxygen sensor.

**[Read the full report](https://ifanirene.github.io/egln1-guinea-pig-report/)**

## Summary

- All 5 catalytic residues (Fe-triad + 2-OG binding site) are invariant across
  54 taxa spanning ~600 Myr, including in guinea pig — no catalytic-site changes.
- 22 guinea-pig-specific substitutions were identified and scored for
  **direction of effect** (enhancement vs. loss-of-function) using ESM-2,
  ESMC-300M, ProteinMPNN (as a structure-conditioned ΔΔG proxy), and MSA
  conservation.
- Top enhancement candidate: **I259V** — a stabilizing, second-shell
  substitution that ancestral-sequence reconstruction shows is a
  **reversion to the deep-ancestral valine**, lost in placental mammals and
  re-acquired in the guinea-pig lineage.

## Contents

- `index.html` — the full report (self-contained, all figures embedded)
- `data/` — supporting tables (mutation scores, mechanism summary, ancestral
  states, sequence/structure provenance)

## Methods

MAFFT + IQ-TREE (JTT+G4, 1000 UFBoot) phylogeny of 54 EGLN1 orthologs/homologs;
IQ-TREE empirical-Bayes ancestral-sequence reconstruction; ESM-2 (650M) and
ESMC-300M masked-marginal scoring; ProteinMPNN structure-conditioned log-odds
on the PHD2 crystal (PDB 5L9B) and AlphaFold model; PyMOL structural rendering.
