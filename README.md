# Biopython-PS1-ACMG
checks which Codons generate same protein change from different nucleotide changes on different nucleotide positions on the codon


Example 1:
Original: TTT
Mutation1: CTT
Mutation2: TTA
Amino Acid: F
Example 2:
Original: TGC
Mutation1: AGC
Mutation2: TCC
Amino Acid: C
Example 3:
Original: AGT
Mutation1: CGT
Mutation2: AGA
Amino Acid: S
Using the provided genetic code, let's decode the original and mutated codons to their corresponding amino acids.

Example 1:

TTT -> F (Phenylalanine)
CTT -> L (Leucine)
TTA -> L (Leucine)
For this example, the original codon TTT codes for Phenylalanine (F). When the first nucleotide is mutated (CTT), it translates to Leucine (L). Similarly, when the last nucleotide is mutated (TTA), it also translates to Leucine (L). Both mutations lead to the same amino acid change.

Example 2:

TGC -> C (Cysteine)
AGC -> S (Serine)
TCC -> S (Serine)
For this example, the original codon TGC codes for Cysteine (C). Both mutations (AGC and TCC) lead to a change to Serine (S).

Example 3:

AGT -> S (Serine)
CGT -> R (Arginine)
AGA -> R (Arginine)
For this example, the original codon AGT codes for Serine (S). Both mutations (CGT and AGA) result in a change to Arginine (R).

For all three examples, two different nucleotide mutations within the same codon result in the same amino acid change, verifying that the output you provided is indeed correct for these cases.
