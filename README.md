# EEOB546_R

This assignment consists of two parts: 
1. Replication of UNIX assignment in R
2. Additional analysis and visualization
3. Two peer-reviewed repositories of two students ("Chiang_review1.Rmd" & "Chiang_review2.Rmd")


## Replication of UNIX assignment in R

1. DATA INSPECTION

Two files were read into the environment: `fang_et_al_genotypes` and `snp_position` using github file path. 
- `fang_et_al_genotypes` contains genetic information about the alleles present at specific SNPs (single nucleotide variations in DNA sequences) in maize, teosinte, and tripsacum samples
- `snp_position` contains location information about the SNPs present in the `fang_et_al_genotypes` file (including Chromosome & specific nucleotide position on the chromosome)

The following data inspection techniques were reviewed for each data frame:
- data frame dimensions (# rows, # columns)
- variable names & data types
- head data frame (examine first 6 rows of data frame)

2. DATA PROCESSING
- filtering for maize & teosinte samples
- selecting appropriate columns
- transposing dfs
- df joining 
- `process_chr_data` function filters joined dfs into appropriate sub-dfs, creates directory, & output files into new directory


## Additional analysis and visualization

This Rmd produces 7 figures (all saved in `figures` folder)
1. distribution of SNP per chromosome (how many SNPs on each chromosome)
2. distribution of SNP occurrences on chromosomes (SNP occurrences across chromosomes in maize and teosinte samples)
3. proportion of homozygous/heterozygous genotypes for each sample 
4. proportion of homozygous/heterozygous genotypes for each group
5. proportion of missing genotype data for each sample
6. proportion of missing genotype data for each group
7. Unique genotype absolute and relative counts across groups

The data frame used to plot these figures was generated in another Rmd (`snp_plot_data_prep`) available in the repository in the `working_files` folder. This file must be read in to generate the figures of this analysis. UPDATE: file path was changed from home computer to git hub, so no alterations to the code will need to be complete. 


## Two peer-reviewed repositories of two students ("Chiang_review.Rmd" & "Chiang_review2.Rmd")

- Two peer reviews were sent to the following students' github repository: Viraaj Vishnu Prasad (https://github.com/Raaj20/BCB5460_R_Assignment/blob/main/Chiang_review.pdf) & Sristi Dey (https://github.com/Sristi2025/BCB546_R_programming/blob/main/Chiang_review2.pdf)
- Two students reviewed this github repository: Memis Bilgici & Zheyuan Zhang (currently awaiting their pull requests containing their reviews)