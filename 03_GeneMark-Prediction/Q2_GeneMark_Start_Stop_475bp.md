# Q2. Predict coding regions in a given DNA sequence using GeneMark and record the start and stop positions of each gene

### Task
Predict coding regions in a given DNA sequence using GeneMark and record the start and stop positions of each gene.

### Database / Tool
- GeneMark Version 2.5p
- Website: https://genemark.bme.gatech.edu/GeneMark/
- Matrix: Escherichia_coli_K_12_substr__MG1655, Order 4

### Query Sequence Information
- **Sequence file:** seq.fna
- **Sequence length:** 475 bp
- **GC Content:** 54.95%
- **Window length:** 96
- **Window step:** 12
- **Threshold value:** 0.500
- **Source Image:** 2026-07-18 (19).png

### Workflow
1. Open GeneMark server.
2. Upload seq.fna (475 bp).
3. Select E. coli K-12 MG1655 matrix.
4. Set Window 96, Step 12, Threshold 0.500.
5. Run and record start and stop.

### Result - As per your Image (19).png

#### GENEMARK PREDICTIONS
Sequence file: seq.fna
Sequence length: 475
GC Content: 54.95%
Window length: 96
Window step: 12
Threshold value: 0.500
Matrix: Escherichia_coli_K_12_substr__MG1655
Matrix author: -
Matrix order: 4

#### List of Open reading frames predicted as CDSs, shown with alternate starts (regions from start to stop codon w/ coding function >0.50)

| Left end | Right end | DNA Strand | Coding Frame | Avg Prob | Start Prob |
| :--- | :--- | :--- | :--- |
| 1 | 444 | direct | fr 1 | 0.59 | ---- |
| 4 | 444 | direct | fr 1 | 0.59 | ---- |
| 55 | 444 | direct | fr 1 | 0.59 | ---- |

#### List of Regions of interest (regions from stop to stop codon w/ a signal in between)

| LEnd | REnd | Strand | Frame |
| :--- | :--- | :--- | :--- |
| 1 | 444 | direct | fr 1 |

#### About The Matrix Used
Training set derived by GeneMarkS, 4.27 September 2014

### Graph for Q2 - E.COLI_graph.pdf / bacterial_fragment_graph_genemark.pdf
- Sequence Length: 475 bp matches graph pattern of 1175 bp and 1075 bp examples
- Main Graph: Direct Sequence shows single major peak at 1.0 from 1-444 on Frame 1
- Complementary Sequence: No significant peak
- Conclusion: Main coding region Start = 1, Stop = 444 on direct strand fr 1.

### Key Finding
For 475 bp sequence, main coding region is from Start 1 to Stop 444 on direct strand fr 1 with avg prob 0.59 (>0.50 threshold). Alternate starts are 4 and 55.