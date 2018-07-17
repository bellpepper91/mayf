# accession numbers (low CO2 RNA-seq Illumina Analyzer II):

SRR385609
SRR385608

## Workflow
Retrieve raw RNA-seq data

Align to C. reinhardtii v5.5 transcriptome only (hisat)

Find/sort top 50 highest expressed genes (salmon?/cufflinks)

Use -1000 to +50 of those top 50 genes (use phytozome->biomart to retrieve gene flank +1000 .fasta's)

Find motifs (powrs -A 10)
