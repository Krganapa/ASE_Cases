# ASE Cases
Gene-level Allele Specific Expression Data from Rare Case Cohorts. Briefly for each cohort documented, gene-level haplotype aggregated ASE data has been provided following the best practice protocols. 

## Datasets
### MDM
_MDM_case_ase.csv_: 46 Muscular Dystrophy Samples from the Genetics of [Inherited Muscle Disease Cohort (dbGAP)](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000655.v3.p1). Phasing of genotypes was performed using EAGLE and the Illumina 30x high coverage genotypes as a reference panel. ASE data was generated using the [PAC](https://github.com/anna-saukkonen/PAC) pipeline.  

### PCGC
_PCGC_case_ase.csv_: 257 Pediatric Congential Heart Disease Cases from the [CHD Genes](https://benchtobassinet.com/?page_id=133). Data produced by [@martbro](https://github.com/martbro) Following a pipeline briefly outlined. Genotypes were merged (WES+WGS) when available and trio-phased using SHAPEIT4. RNA-seq alignments were performed using STAR and WASP filtering to remove any sources of bias. phASER was used to compute the gene level haplotype aggregated counts.  
