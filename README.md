### Preprocessing and figure creations
The Python notebook performs the following steps to create Figure 5:

1. Filter the fastq files from each round of selection and retain only the high quality sequences
2. Trim all the sequences to include only the region of interest, between the constant flanking regions
3. Plot Figure 5a, the number of sequences each distance from RS1 for each round
4. Plot Figure 5b, the abundance of the sequences with >100 reads in CS3 over all rounds

### Data
The raw data have the following filenames:
'ppp-1_S1_L001_R2_001.fastq',
             'ppp-2_S2_L001_R2_001.fastq',
             'ppp-3_S3_L001_R2_001.fastq',
             'ppp-4_S4_L001_R2_001.fastq',
             'ppp-5_S5_L001_R2_001.fastq',
             'ppp-6_S6_L001_R2_001.fastq'

The clustered sequences has the following filename: ppp_clusters.csv

### Output
Two heatmap figures, Figure 5a and 5b, are found in the figures folder.
