# BLASTN Analysis of a Nucleotide Sequence

## Task

Performed BLASTN analysis of a given nucleotide sequence against the NCBI Nucleotide Database to identify significant sequence matches and assess nucleotide-level similarity.

## Database / Tool

- NCBI BLASTN
- NCBI Nucleotide Database

## Input / Sequence Information

- **Sequence type:** Nucleotide sequence
- **Reference sequence identified in the alignment:** *Homo sapiens* mitochondrial genome
- **NCBI Accession:** LS998738.1
- **Aligned region:** 1–385 bp
- **Reference sequence length:** 16,569 bp

## Workflow

The nucleotide sequence was searched against the NCBI Nucleotide Database using BLASTN. Significant hits were evaluated based on sequence identity, E-value, query coverage, and pairwise alignment.

## Result.

### Retrieved / Analysis Output

The BLASTN search produced significant matches to mitochondrial sequences from *Homo sapiens* and other primates. The pairwise alignment with the *Homo sapiens* mitochondrial genome (LS998738.1) showed **384/385 identical nucleotides (99% identity)**, with **1 gap** and an **E-value of 0.0**.

Representative high-similarity matches included:

- *Pan troglodytes* — Cytochrome c oxidase subunit I — **98.83% identity**
- *Gorilla gorilla* — Cytochrome c oxidase subunit I — **97.87% identity**
- *Homo sapiens* — NADH dehydrogenase subunit 5, partial — **100% identity**
- *Pan paniscus* — NADH dehydrogenase subunit 5 — **93.78% identity**
- *Hylobates lar* — NADH dehydrogenase subunit 5 — **85.59% identity**

## Key Finding

The BLASTN results demonstrated high nucleotide-level similarity between the analyzed sequence and mitochondrial sequences, particularly among primate species. The near-perfect pairwise alignment supports strong sequence conservation within the identified mitochondrial region.

## Skills Demonstrated

- NCBI BLASTN
- NCBI Nucleotide Database
- Nucleotide sequence analysis
- Sequence similarity searching
- Pairwise sequence alignment
- Interpretation of sequence identity, E-value, and query coverage
- Comparative genomics
