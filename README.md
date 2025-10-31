# Synuclein Bioinformatics Analysis

Comparative bioinformatics study of **α-, β-, γ-synuclein** and **prion protein (PrP)**  
to explore molecular factors underlying prion-like spreading in α-synuclein.

---

## Objective
To determine why **α-synuclein** exhibits prion-like propagation,  
while its homologs **β- and γ-synuclein** do not,  
and how similar α-synuclein is to the **true prion protein (PrP)** in sequence and structure.

---

## Analysis Plan

1. **Sequence collection (UniProt + orthologues)**  
   - α-, β-, γ-synuclein and PrP  
   - orthologues (human, mouse, zebrafish, chicken…)

2. **Sequence-based predictions**  
   - **PLAAC / PAPA:** prion-like domains  
   - **IUPred2A:** intrinsic disorder  
   - **SEG:** low-complexity regions  
   - **ProtScale:** hydrophobicity profiles

3. **Comparative analysis**  
   - MSA (Clustal Omega), dot plots, heatmaps

4. **Evolutionary context**  
   - Orthology search (MMseqs2 / Ensembl)  
   - Phylogenetic tree

5. **Structural modeling**  
   - AlphaFold2: WT and mutations (A30P, E46K, A53T)

6. **Integration**  
   - Cross-comparison with PrP  
   - Identification of NAC domain as prion-like core

---

## Folder Structure
01_data/ – sequences, orthologues (FASTA)

02_predictions/ – outputs from PLAAC, IUPred2A, SEG, ProtScale

03_comparisons/ – MSA, dot plots, heatmaps

04_structures/ – AlphaFold models, visualizations

05_figures/ – poster and presentation figures

06_docs/ – notes, methods, results, references


---

## Expected Outcome
- NAC domain is conserved among synucleins  
- Only α-synuclein combines **low complexity**, **high disorder**, and **hydrophobicity** → aggregation core  
- α-synuclein shares partial prion-like signatures with PrP but in a distinct structural context

---

**Author:** Bc. Patrícia Grznárová  
*Faculty of Natural Sciences, Comenius University, 2025*

