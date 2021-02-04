Polymorphic Duplication

This is the code and data repository for the polymorphic duplication project entitled "Dosage sensitivity and duplication integrity shapes the landscape of polymorphic duplicates in Drosophila and humans".

Index

Trinity-assembled-transcripts-fusion-gene-Drosophila.fasta file contain all the assembled chimeric transcripts caused by duplication in Drosophila. Taking "Drosophila-2-RAL-379-MFB2-c15570_g2_i2" as an example, each header is intepreted as: species, locus ID, line, tissue (replicate ID) and unique ID generated by trinity. Trinity-assembled-transcripts-fusion-gene-Drosophila-split.fasta file contain all the 5' and 3' reads (split based on breakpoints) derived from Trinity-assembled-transcripts-fusion-gene-Drosophila.fasta. For example, "Drosophila-2-RAL-379-MFB2-c15570_g2_i2.1" and "Drosophila-2-RAL-379-MFB2-c15570_g2_i2.2" represents the 5' segment and 3' segment of "Drosophila-2-RAL-379-MFB2-c15570_g2_i2" seperately.

Trinity-assembled-transcripts-fusion-gene-human.fasta file contain all the assembled chimeric transcripts caused by duplication in humans. Taking "Human-LUMPY-70.SRR1101931.c4_g1_i1" as an example, each header is intepreted as: species, locus ID, NCBI SRA ID and unique ID generated by trinity. Similarly, Trinity-assembled-transcripts-fusion-gene-human-split.fasta file contain all the split reads derived from Trinity-assembled-transcripts-fusion-gene-human.fasta. Since fly RNA-seq data are stranded and human RNA-seq data are unstranded, ".1" and ".2" in human simply refers to the leading and lagging sequence in assembled contigs. 

RT-PCR-transcripts-fusion-gene-Drosophila.fasta file contain all the Sanger sequencing data of the RT-PCR experiments for chimeric transcripts in Drosophila. Taking "RT-PCR-Drosophila-13-RAL-208-L" as an example, each header is intepreted as: species, locus ID, line, sequencing orientation (forward, L; Reverse, R). Similarly, RT-PCR-transcripts-fusion-gene-Drosophila-split.fasta file contain all the split reads derived from RT-PCR-transcripts-fusion-gene-Drosophila.fasta.