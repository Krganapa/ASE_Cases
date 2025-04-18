# ASE Cases
Gene-level Allele Specific Expression Data from Rare Case Cohorts. Briefly for each cohort documented, gene-level haplotype aggregated ASE data has been provided following the best practice protocols. For further information refer to our paper [here]().


## Data Format
Each file is an excel file with the following:
* Each row corresponds to a gene ID (idenitifed by ENSEMBL ID)
* Each column is a sample ID with corresponding values being the gene-level (reference count, alternate count, and ANEVA-DOT p-value) for outlier testing.
* For details on what tissues were used for ANEVA-DOT testing please read our paper [here]()



## Datasets
### MDM
_mdm_cases.xlsx_: 46 Muscular Dystrophy Samples from the Genetics of [Inherited Muscle Disease Cohort (dbGAP)](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000655.v3.p1). Phasing of genotypes was performed using EAGLE and the Illumina 30x high coverage genotypes as a reference panel. ASE data was generated using the [PAC](https://github.com/anna-saukkonen/PAC) pipeline.  

### PCGC
_pcgc_cases.xlsx_: 257 Pediatric Congential Heart Disease Cases from the [CHD Genes](https://benchtobassinet.com/?page_id=133). Data produced by [@martbro](https://github.com/martbro) Following a pipeline briefly outlined. Genotypes were merged (WES+WGS) when available and trio-phased using SHAPEIT4. RNA-seq alignments were performed using STAR and WASP filtering to remove any sources of bias. phASER was used to compute the gene level haplotype aggregated counts.  
