#### Description
This is a general pipeline to do validation for functional genes of interested disease in UKB.

#### Steps
1. Find case and control group information from UKB, based on plink genetic PCA similarity.
2. Find target genes, based on Pathogenesis. Here assumes this step is done.
3. Subset WES plink file of target genes of case and control groups, + - 1MB for each gene.
4. Association analysis for snps to see if they are different between case and control.
5. Function analysis, like eQTL, kept empty here.

![img](https://github.com/Ermineyo/UKBB/blob/main/Find_WES_snp_case_control/img/pipeline_yanbing.png)
