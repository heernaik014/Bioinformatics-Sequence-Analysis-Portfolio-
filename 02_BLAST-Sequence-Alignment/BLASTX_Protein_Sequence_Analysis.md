# BLASTX Analysis - Nucleotide to Protein

## Task
Perform BLASTX analysis of a nucleotide sequence to determine the possible encoded protein.

## Tool Used
NCBI BLASTX - blast.ncbi.nlm.nih.gov
Database: ClusteredNR

## Input / Sequence Information
- Query ID: lcl|Query_6400196
- Description: NC_012920.1 Homo sapiens mitochondrion, complete genome
- Molecule type: dna
- Query Length: 16568 bp
- Program: BLASTX (translates nucleotide to 6 reading frames and searches against protein database)

## Result - Possible Encoded Protein

### Graphic Summary
Distribution of top 100 Blast Hits showed two major clusters:
1. Region ~6000-9000 bp - NADH dehydrogenase subunit 5
2. Region ~12000-14000 bp - Cytochrome c oxidase subunit I
All hits with Score >=200 (Red), indicating highly significant matches.

### Best Hit - Top Encoded Protein

- **Encoded Protein:** NADH dehydrogenase subunit 5 [Pan paniscus]
- **Sequence ID / Accession No:** NP_008209.1
- **Length:** 603 aa
- **Range:** 25 to 587 (in protein) / Query 12409 to 14038
- **Score:** 941 bits (2431)
- **E-value:** 0.0
- **Identities:** 528/563 (94%)
- **Positives:** 540/563 (95%)
- **Gaps:** 0/563 (0%)
- **Frame:** +1

Second significant encoded protein:
- Cytochrome c oxidase subunit I [Pan troglodytes]
- Accession: NP_008188.1
- Score: 914 bits, E-value: 0.0, Identity: 98.83%

## Conclusion
The given nucleotide sequence (Homo sapiens mitochondrial genome, 16568 bp) encodes mitochondrial proteins. The major possible encoded protein identified by BLASTX is **NADH dehydrogenase subunit 5** with Accession No. **NP_008209.1** showing 94% identity and E-value 0.0. The +1 reading frame translation shows it is a functional protein-coding gene. Another protein cytochrome c oxidase subunit I is also encoded in this mitochondrial genome.