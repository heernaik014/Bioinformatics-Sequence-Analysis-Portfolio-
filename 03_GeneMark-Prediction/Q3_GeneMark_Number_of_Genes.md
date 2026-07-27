# Q3. Using GeneMark, determine the number of genes present in the provided nucleotide sequence

### Task
Using GeneMark, determine the number of genes present in the provided nucleotide sequence.

### Database / Tool
- GeneMark.hmm PROKARYOTIC Version 3.42
- Model File: /home/genemark/parameters/prokaryotic/Bacillus_subtilis_168/GeneMark_hmm_combined.mod
- Model: Bacillus_subtilis_168
- RBS: true

### Query Information
- Date: Sun Jul 26 12:27:44 2026
- Sequence File: seq.fna
- Sequence Length: 696 bp
- GC Content: 44.54%
- Window: 96 bp, Step: 12 bp, Threshold: 0.500

### Result - GeneMark.hmm Output

**Predicted genes:**

- Gene #1: Strand + | LeftEnd 1 | RightEnd 696 | Gene Length 696 | Class 2

**Graph Analysis:**
- Graph File: bacillus_subttiles_graph.pdf
- Direct Sequence shows 1 continuous peak from 1 to 696 at 1.0 probability
- Complementary Sequence shows no peak

### Final Answer
**Number of genes present = 1**

- Single gene predicted on + strand from 1 to 696
- Length: 696 bp, Class 2
- Indicates one functional protein-coding gene present in the provided 696 bp sequence.

### Skills Demonstrated
- Gene counting using GeneMark.hmm
- Bacillus subtilis model analysis
- Graph interpretation