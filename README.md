# README for shattering_blast
This repository contains code that was used to perform Basic Local Alignment Search Tool (BLAST) Analysis to find Northern Wild Rice (NWR) orthologs using FASTA files containing sequences of known shattering loci from other species (especially _Oryza_ species).

[shattering_blast.sh](shattering_blast.sh) is the script was used to run the analysis. The file [shattering_fasta_list.txt](shattering_fasta_list.txt) is needed for the script to run. It contains the list of genes we want to blast against the NWR genome to find NWR orthologs of shattering genes from other species. The file [blast_for_shattering_genes.txt](blast_for_shattering_genes.txt) is the precursor to [shattering_blast.sh](shattering_blast.sh) and contains multiple commands that are virtually identical to each other. **Note:** This was done before the PBS-to-SLURM conversion so if you want to re-run this, you would need to change the header syntax.

FASTA files for each of the genes of interest are located in the [FASTA_input](FASTA_input) directory.
