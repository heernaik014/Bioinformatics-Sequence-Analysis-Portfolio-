# TBLASTN Analysis - Hemoglobin Beta (HBB)

## Task
Perform TBLASTN analysis of a protein sequence to find coding nucleotide sequence.

## Tool Used
NCBI TBLASTN - blast.ncbi.nlm.nih.gov
Database: core_nt

## Input Details
- Job Title: Protein Sequence
- RID: 6CS49YYW016 (Search expires on 07-28 03:31 am)
- Program: TBLASTN
- Database: core_nt
- Query ID: lcl|Query_7107487
- Description: unnamed protein product
- Molecule Type: amino acid
- Query Length: 147 aa

## Result - Graphic Summary
- Distribution of the top 100 Blast Hits on 100 subject sequences
- Alignment Scores: >=200 (Red color) for all 100 hits
- All hits highly significant (100% query coverage)
- Example Hit: Synthetic construct Homo sapiens clone IMAGE:100002185 - Score: 301 - Evalue: 1.3e-102 - Accession: AM393351.1

## Result - Top Significant Alignments

### 1. Best Hit - Closest Nucleotide Sequence
- Description: Synthetic construct clone IMAGE:100005789; FLH194450.01X; RZPDo839B0680D hemoglobin, beta (HBB) gene, encodes complete protein
- Sequence ID: DQ893159.2
- Length: 484
- Score: 302 bits (773)
- Expect: 6e-103
- Identities: 147/147 (100%)
- Positives: 147/147 (100%)
- Gaps: 0/147 (0%)
- Frame: +2
- Range: 23 to 463
- Alignment: 100% match from Query 1 to 147

### 2. Second Hit
- Description: Synthetic construct Homo sapiens clone FLH130860.01L hemoglobin beta (HBB) mRNA, partial cds
- Sequence ID: AY894014.1
- Length: 444
- Score: 301 bits (771)
- Expect: 8e-103
- Identities: 147/147 (100%)
- Range: 1 to 441 - Frame +1

### 3. Other Top Hits (All 100% Identity)
- Synthetic construct Homo sapiens clone FLH028845.01L hemoglobin beta (HBB) mRNA, partial cds - AY892640.1 - 301 bits - 8e-103 - 100%
- Homo sapiens full open reading frame cDNA - CR541913.1 - 301 bits - 1e-102 - 100%
- Human messenger RNA for beta-globin - V00497.1 - 301 bits - 9e-102 - 100%
- Homo sapiens hemoglobin subunit beta (HBB) mRNA - NM_000518.5 - 301 bits - 9e-102 - 100%

All 100 sequences selected show 98.64% to 100% identity, 100% Query Cover, E-value 6e-103 to 7e-98.

## Conclusion
The 147 aa protein query encodes **Hemoglobin subunit beta (HBB) gene [Homo sapiens]**. 
The closest nucleotide sequence is **DQ893159.2** - Synthetic construct clone IMAGE:100005789 hemoglobin beta gene with Score 302 bits, E-value 6e-103, 100% identity (147/147) and 100% query cover. 
Graphic Summary shows all Top 100 hits have Score >=200 (Red), confirming highly conserved HBB gene across human clones and other primates.