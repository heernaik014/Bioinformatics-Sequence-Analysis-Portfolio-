# BLASTP Analysis of a Protein Sequence

## Task
Performed BLASTP analysis of a given protein sequence against the NCBI Protein Database to identify significant sequence matches and record the best hit with accession number.

## Database / Tool
- NCBI BLASTP
- ClusteredNR Database
- NCBI Protein Database

## Input / Sequence Information
- Sequence type: Amino acid sequence
- Description: NP_001035835.1 insulin, isoform 2 precursor [Homo sapiens]
- Query ID: lcl|Query_1115954
- Query Length: 200 aa
- Molecule type: amino acid

## Workflow
The protein sequence was searched against the ClusteredNR database using BLASTP. Significant hits were evaluated based on Max Score, E-value, percent identity, query coverage, and conserved domain analysis.

## Result

### Retrieved / Analysis Output
The BLASTP search produced 100 clusters with significant alignments. The top hit showed 100% identity.

**Best Hit Details:**
- Description: insulin, isoform 2 precursor [Homo sapiens]
- Accession Number: NP_001035835.1
- Sequence ID: NP_001035835.1
- Length: 200 aa
- Range: 1 to 200
- Score: 400 bits (1028)
- Expect (E-value): 2e-140
- Identities: 200/200 (100%)
- Positives: 200/200 (100%)
- Gaps: 0/200 (0%)
- Method: Compositional matrix adjust

**Pairwise Alignment:**
Query 1-200 showed 100% match with Subject 1-200.

**Conserved Domain Analysis (Graphic Summary):**
- Specific hit: IIGF_insulin_like
- Superfamily: IlGF_like
- Putative conserved domains detected in the query region.

### Distribution
Distribution of the top 100 Blast Hits on 100 subject clusters showed scores >=200 (Red) for top hits and 80-200 (Purple) for insulin family members.

## Key Finding
The BLASTP results confirmed the query protein as Human Insulin, isoform 2 precursor with Accession No. NP_001035835.1. The E-value of 2e-140 and 100% identity indicates a highly significant and exact match. Domain analysis confirms it belongs to Insulin-like Growth Factor superfamily.

## Skills Demonstrated
- NCBI BLASTP
- Protein sequence analysis
- Interpretation of E-value and percent identity
- Conserved domain identification
- Graphic summary interpretation