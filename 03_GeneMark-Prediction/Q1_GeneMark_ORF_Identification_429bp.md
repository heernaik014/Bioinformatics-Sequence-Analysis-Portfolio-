# Q1. Use GeneMark to analyze a given nucleotide sequence and identify the predicted genes (ORFs)

### Task
Use GeneMark to analyze a given nucleotide sequence and identify the predicted genes (ORFs).

### Database / Tool
- GeneMark Version 2.5p
- Website: https://genemark.bme.gatech.edu/GeneMark/
- Matrix: Escherichia_coli_K_12_substr__MG1655, Order 4

### Query Sequence Information
- **Sequence file:** seq.fna
- **Sequence length:** 429 bp
- **GC Content:** 64.80%
- **Window length:** 96
- **Window step:** 12
- **Threshold value:** 0.500
- **Source Image:** 2026-07-18 (20).png

### Workflow
1. Open GeneMark server.
2. Upload seq.fna (429 bp).
3. Select E. coli K-12 MG1655 matrix.
4. Set Window 96, Step 12, Threshold 0.500.
5. Run GeneMark.

### Result - As per your Image (20).png

#### GENEMARK PREDICTIONS
Sequence file: seq.fna
Sequence length: 429
GC Content: 64.80%
Window length: 96
Window step: 12
Threshold value: 0.500
Matrix: Escherichia_coli_K_12_substr__MG1655
Matrix author: -
Matrix order: 4

#### List of Open reading frames predicted as CDSs, shown with alternate starts (regions from start to stop codon w/ coding function >0.50)

| Left end | Right end | DNA Strand |  0.12 |

**ORFs Predicted (Start to Stop):**
- **ORF 1:** 1 to 429 | Strand: direct | Frame: fr 1 | Avg Prob: 0.83
- **ORF 2:** 4 to 429 | Strand: direct | Frame: fr 1 | Avg Prob: 0.83
- **ORF 3:** 97 to 429 | Strand: direct | Frame: fr 1 | Avg Prob: 0.81

#### List of Regions of interest (regions from stop to stop codon w/ a signal in between)

LEnd | REnd | Strand | Frame |
| :--- | :--- | :--- | :--- |
| 1 | 429 | direct | fr 1 |

#### About The Matrix Used
Training set derived by GeneMarkS, 4.27 September 2014

### Graph for Q1 - HBA_gen_graph_14.pdf
- Sequence Length: 429 bp, GC: 64.80%
- Graph File: seq.fna_for_gm, Order 4, Window 96, Step 12, 2/2
- Direct Sequence: Single continuous peak at 1.0 from 1-429 on Frame 1
- Complementary Sequence: No peak
- Conclusion: 1 main ORF from 1-429 on direct strand fr 1.

### Key Finding
429 bp sequence shows one main predicted gene from 1-429 on direct strand fr 1 with prob 0.83. This is the answer for ORF identification.