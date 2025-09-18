This repository contains the analysis used in my dissertation. The workflow consists of a series of scripts for genotype data processing, quality control, genome-wide association studies (GWAS), and downstream analyses such as polygenic risk scores (PRS).

01_convert_vcf_plink – Convert raw VCF files into PLINK format.
02_preprepared_updates – Apply updates/patches to genotype data.
03_quality_control – Quality control procedures
04_PCA – Principal component analysis for population stratification.
05_merge_IH – Merge intermediate datasets (HumanCore and Infinium).
06_GWAS – Genome-wide association study.
07_format – Format summary statistics and results, included to show conversion to beta.
08_METAL – Meta-analysis using METAL (chromosome and position were added back in after this step).
09_fine_mapping – Fine-mapping of association signals.
10_munge – Munge summary statistics for downstream tools.
11_LDSC – LD Score Regression.
12_MHC – Special handling of the MHC region (see exclude.txt).
13_euro_only – Restrict analysis to European-ancestry samples.
14_PRS – Polygenic risk score construction.
