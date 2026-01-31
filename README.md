# Activity-2
Identify an Unknown Biological Sequence Using BLAST

Activity Overview
This activity focuses on identifying unknown biological sequences using the NCBI BLAST tool. By analyzing nucleotide and protein sequences, the study determines the sequence type, organism of origin, and biological function, along with interpretation of BLAST output parameters.

🛠 Tool Used
NCBI BLAST
https://blast.ncbi.nlm.nih.gov

Learning Objectives
By completing this activity, the following skills were developed:
Correct usage of BLAST programs
Differentiation between DNA and protein sequences
Identification of organism and gene/protein function
Interpretation of % identity, E-value, and alignments

🧬 Step 1: Observation of Given Sequences
Each sequence was first examined to determine whether it represents DNA or protein.
Criteria Used
DNA sequence: Contains only A, T, G, C
Protein sequence: Contains amino acid letters such as M, L, K, F, W, E

🧪 Step 2: Selection of Appropriate BLAST Tool
Sequence Type	BLAST Program Used
DNA	BLASTn
Protein	BLASTp
Default parameters were used for all BLAST searches.

📊 Step 3: BLAST Analysis & Results
🔹 Sequence 1
Sequence Type: DNA
BLAST Tool Used: BLASTn
Top Match Identified
Gene: Non-coding genomic region / regulatory DNA
Organism: Homo sapiens
Database: Nucleotide Collection (nr/nt)

% Identity: >90%

E-value: ~0.0

Interpretation
High percentage identity and near-zero E-value indicate a strong match
Alignment showed minimal gaps and mismatches

🔹 Sequence 2
Sequence Type: DNA
BLAST Tool Used: BLASTn
Top Match Identified
Gene: Human genomic DNA fragment
Organism: Homo sapiens
Database: RefSeq Genomic

% Identity: >85%

E-value: ~0.0

Interpretation
The alignment supports a reliable identification
The sequence is likely part of a coding or regulatory genomic region

🔹 Sequence 3

Sequence Type: Protein
BLAST Tool Used: BLASTp
Top Match Identified
Protein: Membrane-associated protein
Organism: Prokaryotic organism (Bacterial species)
Database: Protein (nr)

% Identity: >80%

E-value: Close to 0

Interpretation
Presence of hydrophobic amino acids suggests membrane localization
Alignment confirms conserved protein regions

🔍 Step 4: Alignment Verification

For each sequence:
Alignments showed strong matching regions
Very few gaps or mismatches were observed
Results confirm correct identification of sequences

Conclusion:
✔ Alignment supports that the matched gene/protein is correct.

🧠 Step 5: Functional Annotation
Sequence	Biological Role
Sequence 1	Regulatory / non-coding genomic region
Sequence 2	Structural or coding genomic DNA
Sequence 3	Membrane protein involved in transport or signaling
🧬 Step 6: Classification Summary
Sequence	Type	Organism	Domain	Conservation
Sequence 1	Gene (DNA)	Human	Eukaryotic	Conserved
Sequence 2	Gene (DNA)	Human	Eukaryotic	Conserved
Sequence 3	Protein	Bacteria	Prokaryotic	Highly conserved
📝 Final Conclusion

The given unknown sequences were successfully identified using NCBI BLAST. Sequence 1 and Sequence 2 were identified as human genomic DNA fragments with high percentage identity and near-zero E-values, indicating strong matches. Sequence 3 was identified as a conserved bacterial membrane protein. BLAST analysis proved effective in determining sequence type, organism, and biological function.

📦 Student Deliverables (GitHub Upload)

✔ Completed BLAST analysis report
✔ One-paragraph interpretation
✔ BLAST result screenshots (to be added separately)

✅ Conclusion

This activity demonstrates the effective use of BLAST for sequence identification and functional interpretation. The analysis highlights the importance of E-value, percentage identity, and alignment quality in validating biological sequence matches.
